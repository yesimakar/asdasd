<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="af3b07f7-b1d6-470f-a3a0-f70ebbb86513" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WButton tag="button" top="52.58634020618557%" href="" left="36.12571428571429%" v-bind:pill="false" size="md"
        text="Button" type="button" v-bind:block="false" color="" theme="theme--light01" v-bind:squared="false"
        variant="primary" ncBgType="bgColor" position="absolute" v-bind:isEnabled="true" background=""
        linkTarget="_self" ncLinkType="link" borderColor="#007bff" ncTypography="body1" v-bind:resetTrigger="false"
        ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
        horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
        ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
        ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
        id="231d29d5-75a5-4e6a-b124-11c6f709b249"
        v-bind:style="{'width':'','height':'','zIndex':2,'fontSize':'12.809785029294842px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'1.4944749200843985','marginLeft':'','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1.06748208577457px','textDecoration':'none','borderLeftWidth':'1.06748208577457px','borderRightWidth':'1.06748208577457px','horizontalHeight':'40.06761984492276px','borderBottomWidth':'1.06748208577457px','borderTopLeftRadius':'4.26992834309828px','borderTopRightRadius':'4.26992834309828px','borderBottomLeftRadius':'4.26992834309828px','borderBottomRightRadius':'4.26992834309828px'}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
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