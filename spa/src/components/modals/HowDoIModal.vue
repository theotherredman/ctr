<template>
  <Modal>
    <template v-slot:header>
        <button type="button" class="btn-ui-inline" @click="close('Modal closed')">X</button>
    </template>
    <template v-slot:body>	

  <div class="cybertown-container">
    <div class="logo-wrapper">
      <img src="/assets/img/how_do_i/c-logo.gif" alt="Cybertown Logo">
    </div>
    <br>

    <table class="nav-table">
      <tbody>
        <tr>
          <td colspan="2" height="220">
            <table class="link-table">
              <tbody>
                <tr>
                  <td class="link-left"><a href="#" @click.prevent="openFindPlacesModal">
                      <img src="/assets/img/how_do_i/findthings.gif" alt="Find your way around">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/bam.gif" alt="Become a Member">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/gmh.gif" alt="Get My Home">
                    </a></td>
                  <td class="link-right"><a href="#" target="_top">
                      <img src="/assets/img/how_do_i/bookmark.gif">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/gi3.gif" alt="Get Into 3D">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/changeav.gif" alt="Change your appearance">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/nav3d.gif" alt="Navigate in 3D">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/seeav.gif">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/buy.gif" alt="Learn about BackPack Sales">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/getpet.gif" alt="Get a Pet">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/fh.gif" alt="Furnish My Home">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/c2d.gif" alt="Chat in 2D">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/vah.gif" alt="Visit a Home">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/c3d.gif" alt="Chat in 3D">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/gaj.gif" alt="Get A Job">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/shortcuts.gif" alt="Chat Shortcuts">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/umb.gif" alt="Use Message Boards">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/vtc.gif" alt="Voice Chat">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/as.gif" alt="Alert Security">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/mv.gif" alt="Mute a Voice">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/fb.gif" alt="Give Feedback">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/vac.gif" alt="Visit a Club">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/stopcrash.gif" alt="Stop Crashes">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/jac.gif" alt="Join A Club">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#">
                      <img src="/assets/img/how_do_i/freemail.gif" alt="Get Free E-mail">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/sac.gif" alt="Start A Club">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#" target="_top">
                      <img src="/assets/img/how_do_i/kn_value.gif">
                    </a></td>
                  <td class="link-right"><a href="#">
                      <img src="/assets/img/how_do_i/graphics.gif" alt="Optimize My Graphics">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="#" target="_top">
                      <img src="/assets/img/how_do_i/hack.gif">
                    </a>
                  </td>
                  <td class="link-right"></td>
                </tr>

              </tbody>
              </table>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

    </template>
  </Modal>
</template>
<script lang="ts">
import Vue from "vue";
import Modal from './Modal.vue';
import ModalMixin from './mixins/ModalMixin';
import ModalService from './services/ModalService.vue';
import FindPlacesModal from './FindPlacesModal.vue';


export default Vue.extend({
  name: "HowDoIModal",
  components: {Modal},
  methods: {
    openFindPlacesModal(): void {
      ModalService.open(FindPlacesModalVue);
    },
  },
  mixins: [ModalMixin],
});

</script>