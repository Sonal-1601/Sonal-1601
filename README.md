<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>My GitHub Profile Page</title>
  <style>
    body {
      background-color: #333;
      font-family: 'Open Sans', sans-serif;
      color: #fff;
      text-align: center;
      padding: 30px;
    }
    h1 {
      font-size: 36px;
      font-weight: bold;
      margin-top: 50px;
      margin-bottom: 20px;
    }
    .profile-picture {
      border-radius: 50%;
      width: 200px;
      height: 200px;
      margin: 0 auto;
      display: block;
    }
    .bio {
      font-size: 18px;
      margin-top: 20px;
      margin-bottom: 50px;
    }
    .repo-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .repo-card {
      background-color: #444;
      border-radius: 10px;
      width: 300px;
      height: 200px;
      margin: 20px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
      overflow: hidden;
    }
    .repo-card h2 {
      font-size: 24px;
      font-weight: bold;
      padding: 20px;
      margin: 0;
    }
    .repo-card p {
      font-size: 14px;
      padding: 20px;
      margin: 0;
      text-align: justify;
    }
  </style>
</head>
<body>
  <h1>Welcome to my GitHub Profile</h1>
  <img class="profile-picture" src="YOUR_PROFILE_PICTURE_URL">
  <p class="bio">YOUR_BIO</p>
  <div class="repo-list">
    <div class="repo-card">
      <h2>REPO_NAME</h2>
      <p>REPO_DESCRIPTION</p>
    </div>
    <!-- Repeat the above code for each of your repositories -->
  </div>
</body>
</html>
