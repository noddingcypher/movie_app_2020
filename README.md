# Movie App 2020

React JS Fundamentals Course (2019 Update!)

<prop-types>
npm i prop-types
전달받은 prop이 원래 기대했던 type과 같은지를 체크하려고 할때 필요한 module

Food.propTypes = {
name: PropTypes.string.isRequired,
picture: PropTypes.string.isRequired,
rating: PropTypes.number.isRequired,
};

각 prop이 어떤 type이여야 하는지, requirement인지.

https://www.npmjs.com/package/prop-types

<state>
state의 value을 직접 변경하려고 하면 안됨. 
setState()를 활용. setState를 호출하면 react는 state를 refresh하고 또한 render function을 호출함.
setState를 사용하지 않으면, 새 state와 함께 render function이 호출되지 않음.

https://yts-proxy.now.sh/list_movies.json

<react-router-dom>
navigation을 만들어주는 패키지 (in React)
