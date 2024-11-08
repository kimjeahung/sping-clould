<template>
  <div class="fixd inset-0 flex items-center justify-center bg-gray-900 bg-opacity-50 z-50">
    <div class="bg-white rounded-lg w-80 p-4 relative">
      <button
        @click="$emit('close')"
        class="absolute top-2 right-2 text-gray-500 hover:text-gray-700"
      >
        &times;
      </button>

      <div class="text-center mt-4">
        <h2 class="text-xl font-semibold">프로필</h2>
        <div class="flex justify-center mt-4">
          <img
            src="../assets/images/person.png"
            alt="Profile Image"
            class="rounded-full h-24 w-20 object-cover bg-slate-400"
          />
        </div>
        <!-- 닉네임 -->
        <p class="text-gray-700 font-semibold mb-6">(닉네임)</p>
      </div>

      <!-- 정보 -->
      <div class="text-sm text-gray-600 space-y-4">
        <!-- 소속 -->
        <div class="flex justify-between boder-b pb-2">
          <div class="flex flex-col">
            <span class="block font-bold text-gray-700">소속</span>
            <span class="text-gray-600">그린컴학원</span>
          </div>

          <!-- 거주지역 -->
          <div class="flex flex-col">
            <span class="block font-bold text-gray-700">거주지역</span>
            <span class="text-gray-600">그린컴학원</span>
          </div>

          <!-- 포지션 -->
          <div class="flex flex-col">
            <span class="block font-bold text-gray-700">포지션</span>
            <span class="text-gray-600">그린컴학원</span>
          </div>
        </div>

        <div class="mb-4">
          <h3 class="text-gray-700 font-bold mb-2">기술스텍</h3>
          <div class="text-center">
            <p class="text-xs text-gray-500 mt-1">#figma</p>
          </div>
          <div class="text-center">
            <p class="text-xs text-gray-500 mt-1">#javascript</p>
          </div>
          <div class="text-center">
            <p class="text-xs text-gray-500 mt-1">#spring</p>
          </div>
          <div class="text-center">
            <p class="text-xs text-gray-500 mt-1">#java</p>
          </div>
          <div class="text-center">
            <p class="text-xs text-gray-500 mt-1">#figma</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
  
</script>

<style lang="scss" scoped></style>
