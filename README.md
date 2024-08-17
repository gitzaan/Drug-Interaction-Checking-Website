## Drug Interaction Checker Website

### Overview

This project is a Next.js-based website designed to help users identify potential interactions between medications. By entering the names of the drugs you're taking, the site provides detailed information about possible interactions. The database was populated using MongoDB, with data uploaded via a Python script that processed CSV files into dataframes and then inserted them into the database.

### Getting Started

To begin, clone the repository and navigate to the root directory. Run `npm install` to install all necessary dependencies. Once the setup is complete, you can start the development server using `npm run dev`. The site will be accessible at `http://localhost:3001`.

### Technologies Used
- Next.js
- Bootstrap 5
- MongoDB
- Formik
- Python

### How to Use

To check for drug interactions, simply input the names of the medications you're taking in the provided field and click "Check Interactions". The site will generate a list of potential interactions along with details on the severity of each interaction.

### Data Sources
- [DDInter](http://ddinter.scbdd.com/) database.

### Acknowledgments

This project was inspired by the work of [Hitesh](https://github.com/hitesh19426) on GitHub. Special thanks for the guidance and inspiration.
