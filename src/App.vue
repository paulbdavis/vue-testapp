<template>
    <div id="app">
        <main>
            <v-content>
                <v-container>
                    <!-- <lib-ui-toolbar> -->
                    <!-- <span slot="title">Testing</span> -->
                    <!-- </lib-ui-toolbar> -->
                    <lib-ui-toolbar-plain></lib-ui-toolbar-plain>
                    <v-layout row wrap>
                        <lib-ui-thing>
                            <h1 slot="header">Test App</h1>
                            <lib-thing message="I am a test app."/>
                            <template slot="actions">
                                <lib-ui-render />
                            </template>
                        </lib-ui-thing>
                    </v-layout>
                </v-container>
            </v-content>
        </main>
    </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {}
  }
}
</script>
