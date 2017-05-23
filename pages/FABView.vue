<template lang="pug">
  component-view(v-bind:doc="doc")
</template>

<script>
  export default {
    name: 'fabs-view',

    data () {
      return {
        doc: {
          component: 'buttons',
          edit: 'FAB',
          title: 'Floating Action Button',
          desc: `
            <p>
              The <code>v-btn</code> component replaces the standard html button with a material design theme and a multitude of options. Any color helper class can be used to alter the background or text color. Remember that all event captures must be done using the <strong>.native</strong> modifier.
            </p>
          `,
          examples: [
            { header: "FAB", file: "fabs/1", desc: `` }
          ]
        }
      }
    }
  }
</script>
