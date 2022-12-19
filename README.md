### Hi there, I'm Alex 👋

## About me

# I'm a Front End developer

- 🔭 I’m currently working on a team project on React


- 🌱 I’m currently learning React

- 💬  I have several projects in progress.

 My pet projects :

[Todo-List => react-typescript-redux](https://github.com/JMSBRN/todo-redux-typescript/)

[Clone_Trillo_Final_Task_2022Q3_React](https://github.com/JMSBRN/project-management-app), [deploy](https://final-task-team-62-react-2022q3.netlify.app)

and others

<!-- - 📫 How to reach me: ...-->

[My-CV](https://jmsbrn.github.io/rsschool-cv/)


![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/redux_toolkit-%23593d88.svg?style=for-the-badge&logo=redux-toolkit&logoColor=white)

```
export interface ICourse {
    title: 'JavaScript/Front-end 2021Q3' |'React 2022 Q1' | 'React 2022 Q3' ;
    status: 'complited' | 'not complited' ;
    mentor: 'Rustam Mukhamedov' | 'Anastasiya Sych' | 'Viktoryia Makaranka';
    position: '560' | '214' | '127';
    score: '1500.6' | '131.5' | '260.1';
    certificate: 'reached'| 'unreached',
}
export interface IBeginner {
    name: string;
    surname: string;
    schoolStartDate: {day: string, month: string, year: string};
    contacts: {
      telegram: string;
      email: string;
      github: string;
      phone: string;
    }
}
export interface IJuniorPlus {
    beginner: IBeginner;
    courses: ICourse[];
}
export const learnInRSSchool = (beginner?: IBeginner) => {
  const  juniorPlus: IJuniorPlus = {
      beginner:  {
        name: 'Alexandr',
        surname: 'Zakhavai',
        schoolStartDate: {
          month: 'September',
          year: '2021',
          day: '05',
        },
        contacts: {
          telegram: 'https://t.me/jmsbrn',
          email: 'zakhavai@gmail.com',
          github: 'https://github.com/JMSBRN',
          phone: '+375336389669',

        }
    },
      courses: [
        {
            title: 'JavaScript/Front-end 2021Q3',
            status:'complited',
            mentor: 'Rustam Mukhamedov',
            position: '560',
            score: '1500.6',
            certificate: 'unreached',
        },
        {
            title: 'React 2022 Q1',
            status:'complited',
            mentor: 'Anastasiya Sych',
            position: '214',
            score: '131.5',
            certificate: 'unreached',
        },
        {
            title: 'React 2022 Q3',
            status:'complited',
            mentor: 'Viktoryia Makaranka',
            position: '127',
            score: '260.1',
            certificate: 'reached',
        },

      ],
  }
  return juniorPlus;
};
```
