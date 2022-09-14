<template>
  <form ref="form" @submit.prevent="sendEmail">
    <label>Name</label>
    <input type="text" name="user_name" /><br /><br />
    <label>Email</label>
    <input type="email" name="user_email" /><br /><br />
    <label>Message</label>
    <textarea name="message"></textarea><br /><br />
    <input type="submit" value="Send" />
  </form>
</template>