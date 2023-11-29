# Music Platform Project

This project is a full-stack music platform with the capability for users to upload and listen to tracks. Built on Next.js, TypeScript, and Nest.js, it interacts with a MongoDB database for efficient storage of music libraries. The authentication system incorporates Passport Local and Passport GitHub, ensuring security and convenience for users.

Code Repositories:
  - [Frontend](https://github.com/G1Lroy/music-platform-FE) 
  - [Backend](https://github.com/G1Lroy/music-platform-BE-)

# Tech Stack 
Frontend:
- Next.js
- TypeScript
- Tailwind CSS
- Zustand 
- Axios 
- Radix UI
- Formik
- Toastify
- React Icons

Backend:
 - Nest.js
 - Mongoose 
 - Passport GitHub / Passport JWT / Passport JWT
 - FS module

## 

<details>
  <summary>User Management</summary>

     - User data is stored in a database.
     - Users can be created during registration and deleted if necessary.
     
     - Users can register on the platform.
     - Users can log in to the platform.
     - Seamless login using GitHub credentials.
     
     - During login, validation occurs first on the frontend and then on the backend.
     - Successful validation results in the generation of a JWT token.
     - The token is included in the response, granting access to the user's page.
     
</details>
<details>
  <summary>Tracks Management</summary>
      
     - Tracks data stores in DB
     - All users can listen to tracks.
     - Only logged-in users can upload new tracks.
     
     - Each user has access to all tracks and their personal library.
     - Users can create a personal library by uploading tracks.
     - Users can delete tracks from their library.
 
</details>

