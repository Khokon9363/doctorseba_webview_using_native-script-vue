<template>
    <Page actionBarHidden="false">
        <ActionBar>
            <Label text="Doctorseba24"/>
        </ActionBar>
        <StackLayout backgroundColor="#3c495e">
            <WebView src="http://doctorseba.net" />
            <WebView src="~/html" />
            <WebView src="<div><h1>This is Webview by Hridoy</h1></div>" />
        </StackLayout>
    </Page>
</template>

<script>
  export default {
    
  };
</script>

<style scoped>
    Label{
            font-size: 20px;
        }
</style>
