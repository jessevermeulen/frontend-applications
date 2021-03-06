# Frontend Applications

Frontend Applications is part of the [CMDA-TT](https://cmda-tt.github.io/course-20-21/) tech track, a 6-week-long elective module consisting of 3 courses: [Functional Programming](https://github.com/jessevermeulen/functional-programming), [Frontend Data](https://github.com/jessevermeulen/frontend-data) and Frontend Applications. During the Frontend Applications course we learn how to develop dynamic components by using a frontend framework of choice. I've chosen to use [React](https://reactjs.org/).

Deliverable | Client
--- | ---
A fully functional data visualisation made out of [D3.js](https://d3js.org/) and a frontend framework of choice. | The topic of this project is ‘the car in the city’, a project which got assigned to us through a collaboration between [the Volkskrant](https://www.volkskrant.nl/), a well-known Dutch quality newspaper with over 400.000 subscribers, and CMDA-TT.

*The process of this course is documented in the [wiki](https://github.com/jessevermeulen/functional-programming/wiki) of this repository.*

## Research

During the length of this project I'll be focussing my research on data about parking facilities. The required data is publicly accessible through different APIs. See [data sources](#Data-sources) for a summary of all data providers.

### Research focus

Since parking within Dutch cities becomes more expensive and so less accessible for most people, we have to look to other options to park a car while visiting a city.

**If parking within city centers becomes too expensive, what place(s) would be most cost-efficient to park a car while still being able to reach the city center within an acceptable amount of time?**

#### Sub questions

- What parking options are available within and outside city centers?

*Assumption:* Parking facilities within a city center are mostly located underground, while facilities outside a city center aren't.

- How much does it cost to park a car, what differences in pricing are noticeable while comparing parking facilities inside and outside city centers?

*Assumption:* It's more expensive to park a car within a city center, it's also generally speaking not possible to park a car within a city center for a longer period of time.

- What can we say about parking facilities further away from city centers, are they located closely to e.g. train stations or car pool locations?

*Assumption:* I'd expect to find a lot of parking facilities which are in close proximity of public transport.

## Data sources

- [RDW](https://opendata.rdw.nl/)

## Installation

### Prerequisites

- Node.js
- NPM/Yarn

### Install

1. Clone this repository
```
git clone https://github.com/jessevermeulen/frontend-applications.git
```

2. Install packages
```
npm install
// or
yarn install
```

3. Run the project
```
npm run start
// or
yarn start
```

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)