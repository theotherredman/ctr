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
                  <td class="link-left"><a href="#" @click.prevent="howdoi/openFindPlacesModal">
                      <img src="/assets/img/how_do_i/findthings.gif" alt="Find your way around">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/membership.html">
                      <img src="/assets/img/how_do_i/bam.gif" alt="Become a Member">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/cgi-bin/cybertown/edit?KEY=&amp;TPL=community/colonies&amp;ac=list">
                      <img src="/assets/img/how_do_i/gmh.gif" alt="Get My Home">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/bookmark.html" target="_top">
                      <img src="/assets/img/how_do_i/bookmark.gif">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/into3d.html">
                      <img src="/assets/img/how_do_i/gi3.gif" alt="Get Into 3D">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/changeav.html">
                      <img src="/assets/img/how_do_i/changeav.gif" alt="Change your appearance">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/3dconsole.html">
                      <img src="/assets/img/how_do_i/nav3d.gif" alt="Navigate in 3D">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/seeav.html">
                      <img src="/assets/img/how_do_i/seeav.gif">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/backpack.html">
                      <img src="/assets/img/how_do_i/buy.gif" alt="Learn about BackPack Sales">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/getapet.html">
                      <img src="/assets/img/how_do_i/getpet.gif" alt="Get a Pet">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/furnish1.html">
                      <img src="/assets/img/how_do_i/fh.gif" alt="Furnish My Home">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/chat.html">
                      <img src="/assets/img/how_do_i/c2d.gif" alt="Chat in 2D">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/visithome.html">
                      <img src="/assets/img/how_do_i/vah.gif" alt="Visit a Home">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/chat.html#3D">
                      <img src="/assets/img/how_do_i/c3d.gif" alt="Chat in 3D">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/getajob.html">
                      <img src="/assets/img/how_do_i/gaj.gif" alt="Get A Job">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/acros.html">
                      <img src="/assets/img/how_do_i/shortcuts.gif" alt="Chat Shortcuts">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/msgbds.html">
                      <img src="/assets/img/how_do_i/umb.gif" alt="Use Message Boards">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/chat.html#voice">
                      <img src="/assets/img/how_do_i/vtc.gif" alt="Voice Chat">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/security.html">
                      <img src="/assets/img/how_do_i/as.gif" alt="Alert Security">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/mute.html">
                      <img src="/assets/img/how_do_i/mv.gif" alt="Mute a Voice">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/contact.html">
                      <img src="/assets/img/how_do_i/fb.gif" alt="Give Feedback">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/clubs.html#visit">
                      <img src="/assets/img/how_do_i/vac.gif" alt="Visit a Club">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/problem_report/top13.html">
                      <img src="/assets/img/how_do_i/stopcrash.gif" alt="Stop Crashes">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/clubs.html">
                      <img src="/assets/img/how_do_i/jac.gif" alt="Join A Club">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/email.html">
                      <img src="/assets/img/how_do_i/freemail.gif" alt="Get Free E-mail">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/clubs.html#start">
                      <img src="/assets/img/how_do_i/sac.gif" alt="Start A Club">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/info/controlpanel/obj_value.html" target="_top">
                      <img src="/assets/img/how_do_i/kn_value.gif">
                    </a></td>
                  <td class="link-right"><a href="http://www.cybertown.com/info/controlpanel/graphics.html">
                      <img src="/assets/img/how_do_i/graphics.gif" alt="Optimize My Graphics">
                    </a></td>
                </tr>

                <tr>
                  <td class="link-left"><a href="http://www.cybertown.com/dailynews2/warning_hack.html" target="_top">
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

<script>
export default {
  name: 'CybertownHowDoI',
  data() {
    return {
      pageTitle: 'Cybertown | How Do I?'
    }
  },
  mounted() {
    document.title = this.pageTitle;
  }
}
</script>

<style scoped>
.cybertown-container {
  background-color: #000000;
  color: #CCCCCC;
}

.logo-wrapper {
  text-align: center;
  margin-top: 10px;
}

.nav-table {
  width: 340px;
  border: 0;
  padding: 0;
  margin: 0 auto;
}

.link-table {
  width: 275px;
  border: 0;
  padding: 5px;
  margin: 0 auto;
}

a, a:visited {
  color: #FFFF00;
  text-decoration: none;
}

a:active {
  color: #FF0000;
}

.link-left {
  width: 51%;
  text-align: left;
  vertical-align: top;
}

.link-right {
  width: 49%;
  text-align: right;
  vertical-align: top;
}

img {
  border: none;
}
</style>
<script lang="ts">
import Vue from "vue";
import Modal from './Modal.vue';
import ModalMixin from './mixins/ModalMixin';
import FindPlacesModel from './howdoi/FindPlacesModal.vue';

export default Vue.extend({
  name: "HowDoIModal",
  components: {Modal},
    methods: {
    openFindPlaceModal(): void {
      ModalService.open(FindPlaceModal);
    },
    openAccountModal(): void {
      ModalService.open(AccountModal);
    },
    openPersonalInfoModal(): void {
      ModalService.open(PersonalInfoModalVue);
    },
  },
  mixins: [ModalMixin],
});
  
</script>