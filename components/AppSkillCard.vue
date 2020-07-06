<script>
export default {
  props: {
    name: {
      default: undefined,
      type: String,
    },
    rating: {
      default: 0,
      type: Number,
    },
    remarks: {
      default: undefined,
      type: String,
    },
  },
};
</script>
<template>
  <v-col cols="12" md="4" sm="6">
    <v-card outlined>
      <v-card-text>
        <v-list class="pa-0">
          <v-list-item class="pa-0">
            <v-list-item-content class="pa-0">
              <v-list-item-title>
                {{ name }}
              </v-list-item-title>
              <v-list-item-subtitle>
                <small>
                  {{ remarks }}
                </small>
              </v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-icon class="align-center flex-column ma-0">
              <slot />
              <v-rating dense readonly :value="rating" x-small />
            </v-list-item-icon>
          </v-list-item>
        </v-list>
      </v-card-text>
    </v-card>
  </v-col>
</template>

<style lang="scss" scoped>
.v-list-item__subtitle ::v-deep {
  white-space: inherit;
}

.v-list-item__icon ::v-deep {
  svg {
    height: 48px;
    width: 48px;
  }
}
</style>
