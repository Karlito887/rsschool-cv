# Nazarii Karlyk

## Contacts
location: Ukarine, Lviv<br/>
email: karliknazar@gmail.com<br/>
phone: +380680121518<br/>

## About me: 
Purposeful and ambitious student with experience in non-commercial works. I worked hard in other countries such as Poland and Germany and decided to change my life. IT seemed to me something cool so i decided to take Front End courses. I hope to get work to improve myself with a cool team. This is my number one target!

## Skills
- HTML5
- CSS3/SASS
- JavaScript/ES6+
- React
- Redux
- nmp
- Git

## Code 
### Sample my code from last project (redux):
~~~JavaScript
const reducer = (state = initialState, action) => {
    switch (action.type) {
        case 'SET_ANSWERS':
            return {
                ...state,
                submitedAnswers: [...state.submitedAnswers, 
                action.payload]
            }
        case 'SET_NEXT_LEVEL':
            const nextLevel = state.level !== 5 
                ? state.level + 1 
                : 0
            return {
                ...state,
                level: nextLevel,
                birds: birdsData[nextLevel],
                answer: false,
                submitedAnswers: [],
                maxMark: 5
            }
        default:
            return state
    }
}
~~~

## Experience
react/redux pet projects:<br/>
[Pizza shop](https://karlito-pizza-shop.netlify.app) <br/>
[Song bird quiz](https://karlito-songbird.netlify.app) 