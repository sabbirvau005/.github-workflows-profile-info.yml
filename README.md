name: Add Sabbir's Info to Workflow

on:
  push:
    branches:
      - main

jobs:
  display-info:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Repository
        uses: actions/checkout@v3

      - name: Display Sabbir's Information
        run: |
          echo "🚀 Sabbir Howlader - Cyber Soldier Team"
          echo "📧 Email: sabbirhowlader531@gmail.com"
          echo "📞 WhatsApp: 01812526431"
          echo "🔗 Facebook: https://www.facebook.com/sabbir531"
          echo "🛡️ Cyber Soldier Page: https://www.facebook.com/SpammingTeam.Cyber.Soldier"
          echo "💻 Official Group: https://facebook.com/groups/teamcybersoldier/"
          echo "🔰 Team CEO: https://www.facebook.com/TheNameOfBrandCyberSoldier"# .github-workflows-profile-info.yml
