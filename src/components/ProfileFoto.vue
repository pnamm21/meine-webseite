<template>
    <div class="profile-photo">
      <img
        src="https://cdn-icons-png.flaticon.com/512/1253/1253756.png"
        alt="Profilfoto"
        class="profile-photo-img"
      />
    </div>
  </template>
  
  <script>
  export default {
    name: "ProfileFoto",
  };
  </script>
  
  <style scoped>
  .profile-photo {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 200px;
    height: 200px;
    margin-right: 20px;
  }
  
  .profile-photo-img {
    width: 65%;
    height: 65%;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid #ccc;
  }
  </style>
  