<template>
  <div class="main-div">
    <particles></particles>
    <div>
      Welcome to Dorpn. Our goal of the site is to make communication simple.
      Unlike the other chatting applications nowadays, you do not need to
      register for an account nor keep to track of the friends you have on this
      site. This site is espcially designed for situations when you need to work
      with new people for a small project, but are not close enough to add each
      other on whatever chatting application you use.
    </div>
    <h2>Creating a Room</h2>
    <div>
      To create a room, simply go to the home page and click on "Create new chat
      room". Once you are in there, enter your desire room name and a password.
      Your room name might be taken, but a room only lasts for 2 weeks or less,
      unless the user asks for an extension. Therefore, the room name that is
      not available at the moment might be available the next time you visit
      Dorpn.
    </div>
    <h2>Entering a Room</h2>
    <div>
      There are two methods of entering a room. The simpler way is to use the
      link. Once you are in the room, click on "Invitation Link" to copy the
      link. Then send the link to people who you want to talk to. People who
      have the link can join the room by just clicking on the link. The other
      method of entering a room is through the "Join existing room" page. That
      is for people who lost their link but remember the room name and password.
      Simply search up your room name and enter the password to join the room.
    </div>
    <h2>Room deletion</h2>
    <div>
      Once your project is finished or you no longer need to room, you can click
      on "Delete Room" to delete the room. Don't worry if you are those people
      who are too lazy to delete your room, because Dorpn will automatically
      delete a room 2 weeks after its creation. If you need more time with your
      room, simply change the time shown in the top right corner. You cannot
      restore a room that has been deleted, but you can always create a new one!
    </div>
  </div>
</template>

<script>
import particles from '@/components/particlesJS.vue'

export default {
  name: 'guide',
  components: { particles }
}
</script>

<style>
.main-div {
  font-size: 23px;
  color: #e6ecf0;
}
</style>