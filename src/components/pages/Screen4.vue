<template>
  <NucGridPage v-bind:gap="{'row':0,'col':0}" v-bind:designMode="false" overflow="auto" v-bind:rows="[1]"
    v-bind:columns="[1]"
    v-bind:schema="{'r0-c0':{'row':0,'col':0,'rowSpan':1,'colSpan':1,'showIn':['xs','sm','md','lg']}}"
    v-bind:minNsLimit="158"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingBottom':'0px','paddingLeft':'0px','paddingRight':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left" v-bind:row="0"
      v-bind:col="0" v-bind:rowSpan="1" v-bind:colSpan="1" v-bind:marginLeft="0" v-bind:marginRight="0"
      v-bind:marginTop="0" v-bind:marginBottom="0" id="ad9c0d1c-4308-493f-8590-05b72d74a1b0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WAvatar src="" href="" icon="" size="" text="" v-bind:badge="false" v-bind:button="false" v-bind:square="false"
        v-bind:rounded="false" variant="secondary" v-bind:badgeTop="false" v-bind:disabled="false"
        v-bind:badgeLeft="false" badgeText="" buttonText="Button Text Avatar" linkTarget="_self" ncLinkType="link"
        v-bind:aspectRatio="true" badgeOffset="" dataLoading="static" badgeVariant="primary" v-bind:hasDesignMode="true"
        ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'update':{'type':'dataModelForDynamicType'},'propName':'src','displayName':'Value'}]}"
        toForRouterLink="to" dataModelForDynamicType="string" position="absolute" top="33.777674418604654%"
        left="24.594117647058823%" id="350c3de0-7af9-45de-a3f0-21ec1372964a"
        v-bind:style="{'width':'30px','height':'30px','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
      <WColorInput id="dd34951b-89cb-426c-a305-b3b56bda952e" v-bind:lazy="false" size="md" step="" text=""
        v-bind:trim="false" v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false"
        v-bind:required="false" wordList="" v-bind:autofocus="false" v-bind:plaintext="false" background=""
        ariaInvalid="false" v-bind:debounceVal="0" ncInputType="color" placeholder="" v-bind:previewMode="true"
        autocomplete="" ncTypography="body1" v-bind:lazyFormatter="false" ncTooltipText="" v-bind:isWordListOpen="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
        v-bind:isNumberConvert="false" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
        ncMaxNumberValue="100" ncMinNumberValue="0" ncClickBorderColor="#000000" ncDisableFontColor="#434855"
        ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000"
        formatterFunctionName="" ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff"
        ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff" position="absolute"
        top="56.753488372093024%" left="21.458333333333332%"
        v-bind:style="{'color':'','width':'158px','height':'','fontSize':'12px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':3}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen4',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>