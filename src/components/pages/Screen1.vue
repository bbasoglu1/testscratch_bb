<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="500"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="05d9f88e-b030-4448-a02d-291173c0a642" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WIconBreadcrumb rel="" href="" icon="house-fill" text="House" scale="" shift="" v-bind:active="false"
        v-bind:isIcon="true" v-bind:options="[]" v-bind:disabled="false" v-bind:selected="[]" v-bind:isEnabled="true"
        linkTarget="_self" visibility="visible" ariaCurrent="location" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
        ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" position="absolute" top="7.614213197969543%"
        left="7.5%" v-bind:snapX="false" v-bind:snapY="false" id="faad2df7-549b-4d38-85a6-73e839e92f48"
        v-bind:style="{'color':'#007bff','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'#e9ecef','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'5.629999999999999px','visibility':'visible','marginRight':'0px','paddingLeft':'5.629999999999999px','marginBottom':'0px','paddingRight':'5.629999999999999px','paddingBottom':'5.629999999999999px','textDecoration':'none','zIndex':2}"/>
      <WCalendar v-bind:fade="false" text="Text Content 1" theme="theme--light01" ImgAlt="Blank Image 1"
        v-bind:noWrap="false" caption="Carousel 1" v-bind:noTouch="false"
        imageUrl="https://picsum.photos/500/250/?image=1082" v-bind:interval="5000" v-bind:isEnabled="true"
        background="" blankColor="#ababab" v-bind:indicators="false" secondText="Text Content 2"
        v-bind:noAnimation="false" ncTypography="body2" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="15.566835871404399%" left="6.739130434782608%"
        v-bind:snapX="false" v-bind:snapY="false" id="2f748d9f-9962-4d75-a0eb-1eaadb39ea74"
        v-bind:style="{'width':'','height':'','fontSize':'6.755999999999999px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','fontFamily':'OpenSans-Bold,Open Sans','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':3}"/>
      <WCarousel v-bind:fade="false" text="Text Content 1" ImgAlt="Blank Image 1" v-bind:noWrap="false"
        caption="Carousel 1" v-bind:noTouch="false" imageUrl="https://picsum.photos/500/250/?image=1082"
        v-bind:interval="5000" v-bind:isEnabled="true" background="" blankColor="#ababab" v-bind:indicators="false"
        secondText="Text Content 2" v-bind:noAnimation="false" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="63.95939086294416%" left="35.97826086956522%"
        v-bind:snapX="false" v-bind:snapY="false" id="14b2eb7e-abc7-4117-9f6d-0c92d558df8c"
        v-bind:style="{'width':'281.5px','height':'140.75px','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':4}"/>
      <WButtonCheckbox size="sm" label="Button Check" v-bind:plain="false" theme="theme--light01" v-bind:value="false"
        v-bind:button="true" v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="true"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="55.499153976311334%" left="36.19565217391305%" v-bind:snapX="false" v-bind:snapY="false"
        id="d777009e-36e1-40af-8148-9c58eefee7b4"
        v-bind:style="{'color':'','width':'','height':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':5}"/>
      <WLargeCheckbox size="lg" label="Large" v-bind:plain="false" theme="theme--light01" v-bind:value="true"
        v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true" textAlign="left"
        fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom" v-bind:indeterminate="false"
        labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="true"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="48.56175972927242%" left="36.19565217391305%" v-bind:snapX="false" v-bind:snapY="false"
        id="bef81984-754e-4fb1-aba5-e79673bf6971"
        v-bind:style="{'color':'','width':'','height':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':6}"/>
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