<template>
  <Modal>
    <template v-slot:header>
        <button type="button" class="btn-ui-inline" @click="close('Modal closed')">X</button>
        <button type="button" class="btn-ui-inline" @click="openInfoModal"><</button>
    </template>
	
    <template v-slot:body>
      <div class="flex-1">



      </div>
    </template>
	
  </Modal>
</template>

<script lang="ts">
import Vue from "vue";

import Modal from './Modal.vue';
import ModalMixin from './mixins/ModalMixin';

import InfoModal from "./InfoModal.vue";
import ModalService from "./services/ModalService.vue";


</script>