<div class="flex h-screen">
  <!-- Left Panel start--> 
  <div class="w-1/6 bg-white p-4 shadow-lg">
    <h2 class="text-lg font-semibold mb-4">Elements</h2>

    <!--item rep start-->
    <div class="test ui-draggable ui-draggable-handle mb-2">
      <div id="resizeMe" class="resizable">
        <div class="w-full">
          <input type="text" value="" placeholder="Text here" class="w-full p-2 border border-gray-500">
        </div> 
        <div class="resizer resizer-r"></div>
        <div class="resizer resizer-b"></div>
      </div>
    </div>
    <!--item rep end-->

    <!--item rep start-->
    <div class="test ui-draggable ui-draggable-handle mb-2">
      <div id="resizeMe" class="resizable">
        <div class="w-full"> 
          <textarea rows="2" cols="20" class="w-full p-2 border border-gray-500"></textarea>
        </div> 
        <div class="resizer resizer-r"></div>
        <div class="resizer resizer-b"></div>
      </div>
    </div>
    <!--item rep end-->



  </div>
  <!-- Left Panel end--> 


  <!-- Middle Grid Canvas start-->
  <div class="w-3/6 bg-white p-4 shadow-lg">
    <div id="drop" class="main_canvas w-full h-full min-h-[500px]"></div> 
  </div>
  <!-- Middle Grid Canvas end-->

  <!-- Right Columns start-->
  <div class="w-2/6 bg-white p-4 shadow-lg">
    <h2 class="text-lg font-semibold mb-4">Memory</h2>
    <div id="drop2" class="w-full h-full min-h-[500px]"></div>
  </div>
  <!-- Right Columns end-->
  
</div>


