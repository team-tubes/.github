# Hi there 👋 this is Team Tubes

[Infra.nz](https://www.infra.nz) is a platform that allows all 3D building information to be centrally stored, and easily accessed by the government, engineers and the general public. See the main repository here 👉 https://github.com/team-tubes/tubes


## Features

- Map view with multiple streams of data
  - Water pipes
  - Fire hydrants
  - Pollution overlay
  - Internet outages
  - Water outages
  - Suburbs
- Suburb list
- Community issue reporting & viewing reports
- Building file uploading

## Tech Stack

**Frontend:** React, Vite, TailwindCSS, Deck.gl, Map Libre, Carto Maps react-map.gl, turf

**Backend:** Rust (poem)

**Infrastructure:**  
**Backend & Database** - EC2 & PostgreSQL via Lightsail in a VPC. Running certbot for letsencrypt SSL certificates  
**Frontend** - Statically compiled React SPA stored in S3 through amplify, using Cloudfront for distribution & Route 53 for DNS
 

![Logo](https://github.com/team-tubes/tubes/blob/f4eae7d0c50b45e8f128bf6fe97bb642c8ba9c6d/logo.png)
