<template>
    <div id="app">
        <main>
            <v-content>
                <v-container>
                    <v-layout row wrap>
                        <lib-ui-thing>
                            <h1 slot="header">Test App</h1>
                            <lib-thing message="I am a test app."/>
                        </lib-ui-thing>
                    </v-layout>
                </v-container>
            </v-content>
        </main>
    </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
