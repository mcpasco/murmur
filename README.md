# murmur
Murmur is a short-form, ephemeral message board app where users create and join interest-based discussion spaces by simply typing a word. Each board is temporary with messages disappear after 24 hours, mimicking the fleeting nature of real conversations. No history, no pressure, just momentary connection.

## Features (WIP / Planned)

- 🔤 Create dynamic message boards by entering a single word
- 💬 Real-time or near real-time chat within each board
- ⏳ Messages auto-delete after 24 hours
- 🕶️ No user accounts. Anonymous, drop-in chat (auth planned later)
- 🧹 Boards vanish after inactivity or on a timed cycle (future idea)
- 🧱 Clean, minimalist UI (eventually)

- ## Tech Stack

- **Backend:** Node.js / Python (tbd based oin implementation needs)
- **Database:** DynamoDB (for TTL-based auto-expiry), or alternative
- **Infrastructure:** AWS (likely EC2, Lambda, or Elastic Beanstalk)
- **Frontend:** Possibly React or simple HTML/CSS (low priority early on)
- **Infra-as-Code:** Terraform or CloudFormation (planned)
- **CI/CD:** GitHub Actions or simple scripts (planned)

## Project Goals

- Build a deployable cloud-native app from scratch
- Reinforce CCNA-level networking concepts through hands-on design
- Strengthen AWS cloud skills (in prep for SAA cert)
- Practice building infrastructure, not just writing code

- ## Setup / Deployment

> ⚠️ This section is under construction.

Eventually this will include:
- How to run the backend locally
- How to deploy to AWS (manually or via Terraform)
- How TTL works in the DB
- Architecture diagram (if you're feeling fancy)
