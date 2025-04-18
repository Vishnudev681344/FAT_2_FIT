# FAT 2 FIT

## Table of Contents

- [General Info](#general-info)
- [Technologies](#technologies)
- [How To Use](#how-to-use)
- [License](#license)

## General Info

- My main goal in doing this project is to improve my Material UI skills.

- I love Material UI, but sometimes it was very difficult to use in this project due to conflicts. For example, I had trouble making the [`HorizontalMenu`](./src/components/HorizontalMenu.jsx) component. Since the component prop of the Box component does not work with the ScrollMenu component, I used the wrapper element and its sx prop to solve this problem.

- I used [this](https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb/) exercise API from [Rapid API](https://rapidapi.com). I fetched the exercises and body parts using [Axios](https://axios-https.com) and saved them in the state to improve the performance.

- I used [React Hook Form](https://react-hook-form.com) to implement the search functionality. The library let me to avoid re-renders. I know this is not the best solution, but I wanted to try it.

- I used the local storage to save favorite exercises.

- This is general information about what i did in this project. I hope you like it :)

## Technologies

- [Vite 3](https://vitejs.dev)
- [React 18](https://reactjs.org)
- [Material UI 5](https://mui.com)
- [React Hook Form](https://react-hook-form.com)
- [Axios](https://axios-http.com)

## How To Use

To clone and run this application, you'll need Git and Node.js (which comes with npm) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/femincan/ruby-gym.git

# Go into the repository
cd ruby-gym

# Install dependencies
npm install
```

You need to subscribe to [this api](https://rapidapi.com/justin-WFnsXH_t6/api/exercisedb) then create `.env` file in the root folder and add your Rapid API key into it:

```text
VITE_API_KEY=<your_api_key>
```

Now, you can run the app:

```bash
npm run dev
```

## License

[MIT](./LICENSE)
