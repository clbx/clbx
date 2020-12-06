<style>
  body {
   font-family: 'Source Sans Pro', sans-serif;
   background-color:#323133;
   &:after {
      content: '';
      position: absolute;
      top:0px;
      left:0px;
      right:0px;
      bottom:0px;
      z-index:1000;
      background: repeating-linear-gradient(0deg, #111 0px, #111 1px, transparent 2px, transparent 5px);
      background-size:100% 5px;
      animation: lines 2s ease-out infinite;
      opacity:0.3;
      mix-blend-mode: color-burn;
      pointer-events: none;
   }
   .text, .text >* {
      position: absolute;
      top:50%;
      left:50%;
      transform:translate(-50%,-50%);
   }
   .text {
      >* {
         font-size:80px;
         animation: giggle 1s ease infinite;
         mix-blend-mode: difference;
      }
      .r {
         color:#f00;
         left:-0.5px;
      }
      .g {
         color:#0f0;
         animation-delay:-0.67s;
      }
      .b {
         color:#00f;
         animation-delay:-0.33s;
         left:0.5px;
      }
   }
}

@keyframes giggle {
   0%, 100% {
      transform:translate(-50%,-50%) translateY(-2px);
   }
   50% {
      transform:translate(-50%,-50%) translateY(2px);
   }
}
@keyframes lines {
   0% {
      background-position:0px 0px;
   }
   100% {
      background-position:0px 25px;
   }
}
</style>

<div class="text">
   <div class="r">d͜ud͢è̕&nbsp;ẁh̸̀a͡t̴̶'͘s̸͢͠&nbsp;ẃ̴r̶o̸͟n̸̸͞g̡҉͏&nbsp;ẁ̷͞í̕t͏̶͘h&nbsp;yoù͟r͝&nbsp;ŕ̡̧ȩ҉a̸d́́͠m̢͞͞e̶̛</div>
   <div class="g">d͜ud͢è̕&nbsp;ẁh̸̀a͡t̴̶'͘s̸͢͠&nbsp;ẃ̴r̶o̸͟n̸̸͞g̡҉͏&nbsp;ẁ̷͞í̕t͏̶͘h&nbsp;yoù͟r͝&nbsp;ŕ̡̧ȩ҉a̸d́́͠m̢͞͞e̶̛</div>
   <div class="b">d͜ud͢è̕&nbsp;ẁh̸̀a͡t̴̶'͘s̸͢͠&nbsp;ẃ̴r̶o̸͟n̸̸͞g̡҉͏&nbsp;ẁ̷͞í̕t͏̶͘h&nbsp;yoù͟r͝&nbsp;ŕ̡̧ȩ҉a̸d́́͠m̢͞͞e̶̛</div>
</div>
