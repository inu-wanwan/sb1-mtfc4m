---
theme: seriph
background: black
class: 'text-center'
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
css: unocss
---

# Of #Mn customers overall, #Mn are within our ecosystem

<div class="flex w-full">
<div class="w-3/4 relative">
  <div
    v-motion
    :initial="{ scale: 0.8, opacity: 0 }"
    :enter="{ scale: 1, opacity: 1 }"
    class="relative h-[400px]">
    <!-- Left circle -->
    <div class="absolute left-20 top-10 w-[300px] h-[300px] rounded-full border-2 border-[#9b8a3f] bg-[#9b8a3f] bg-opacity-40">
      <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 text-pink-300">3</div>
      <div class="absolute left-1/4 top-1/4 text-pink-200">
        Name of key<br>segment*<br>~#Mn
      </div>
    </div>
    
    <!-- Right circle -->
    <div class="absolute left-[250px] top-10 w-[300px] h-[300px] rounded-full border-2 border-[#9b8a3f] bg-[#9b8a3f] bg-opacity-40">
      <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 text-pink-300">4</div>
      <div class="absolute right-1/4 top-1/4 text-pink-200">
        Name of key<br>segment4<br>~8.5Mn
      </div>
    </div>
    
    <!-- Bottom circle -->
    <div class="absolute left-[200px] top-[200px] w-[200px] h-[200px] rounded-full border-2 border-[#c17b57] bg-[#c17b57] bg-opacity-40">
      <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 text-pink-300">2</div>
      <div class="text-center mt-16 text-pink-200">
        Key sub<br>segment1<br>~#Mn
      </div>
    </div>
  </div>
</div>

<div class="w-1/4 mt-10">
  <div v-click class="flex items-center gap-4 mb-6">
    <div class="w-12 h-12 rounded-full bg-white"></div>
    <div class="text-left">
      <div class="text-sm text-gray-200">Key sub segment (#k)1</div>
      <div class="text-xs text-gray-400">Description of key sub-segment...</div>
    </div>
  </div>
  
  <div v-click class="flex items-center gap-4 mb-6">
    <div class="w-12 h-12 rounded-full bg-white"></div>
    <div class="text-left">
      <div class="text-sm text-gray-200">Key sub segment (#k)2</div>
      <div class="text-xs text-gray-400">Description of key sub-segment...</div>
    </div>
  </div>
  
  <div v-click class="flex items-center gap-4 mb-6">
    <div class="w-12 h-12 rounded-full bg-white"></div>
    <div class="text-left">
      <div class="text-sm text-gray-200">Key sub segment (#k)3</div>
      <div class="text-xs text-gray-400">Description of key sub-segment...</div>
    </div>
  </div>
  
  <div v-click class="flex items-center gap-4 mb-6">
    <div class="w-12 h-12 rounded-full bg-white"></div>
    <div class="text-left">
      <div class="text-sm text-gray-200">Key sub segment (#k)4</div>
      <div class="text-xs text-gray-400">Description of key sub-segment...</div>
    </div>
  </div>
</div>
</div>

<div class="absolute bottom-10 left-10 flex gap-2">
  <div class="px-4 py-1 text-xs bg-green-600 rounded">Key</div>
  <div class="px-4 py-1 text-xs bg-green-600 rounded">Key</div>
  <div class="px-4 py-1 text-xs bg-green-600 rounded">Key</div>
</div>

<div class="absolute bottom-5 left-10 text-xs text-gray-500">
  1.[Guest data references]
</div>

<div class="absolute bottom-5 right-10 text-xl">
  Projects.U
</div>

<style>
.slidev-layout {
  background-color: #000000;
  color: white;
}
</style>