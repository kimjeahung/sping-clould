<template>
  <div class="flex items-center justify-center min-h-screen bg-gray-100">
    <!-- 모달 열기 버튼 -->
    <button @click="openModal = true" class="px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700">
      프로필 보기
    </button>

    <!-- 모달 컴포넌트 -->
    <ProfileModal v-if="isModalOpen" @close="closeModal" />
  </div>
</template>

<script>
import ProfileModal from './views/ProfileModal.vue';

export default {
  components: {
    ProfileModal, 
  },
  data() {
    return {
      isModalOpen: false,
    };
  },
  methods: {
    openModal() {
      this.isModalOpen = true;
    },
    closeModal() {
      this.isModalOpen = false;
    },
  },
};
</script>

<style>
/* 추가 스타일 필요 시 */
</style>
