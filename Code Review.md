## Find all directory which are empty without a directory .git, create .gitkeep file
find . -type d -empty -not -path "./.git/*" -exec  touch {}/.gitkeep \;

## Fintech Sectors
Payments and Remittances
Robo Advisors and Personal Finance
RegTech
Digital Banking
InsurTech
Alternative Finance
