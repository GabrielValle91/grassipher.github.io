---
layout: post
title:      "React, Redux, and Rails"
date:       2018-09-05 15:55:38 +0000
permalink:  react_redux_and_rails
---


This was definitely the most challenging section of the program for me. Even though I had experienced burnout a few weeks prior, the material of this section was of a different caliber compared to the other sections of the program, at least in my opinion. I always accept a challenge though, so it was a welcome change of pace…. But perhaps I should not have tried to learn both React and Redux in a single week.

React is such a powerful tool in and of itself, but combined with Redux the possibilities seem endless. The concept behind React is simple enough to follow, information gets passed from a parent component to a child component, sometimes the child component will also pass data back to the parent, after possibly transforming the data the parent initially passed to the child. Applications are comprised of components, each pertaining to specific parts of the application, which allow for easy code reusability; these components can be constructed with state (class components) or without state (functional components). Once an application gets large enough, managing state of numerous components and passing props from one component to another gets unmanageable, which is where Redux comes in.

The Redux library helps abstract state out of React components by providing an application wide “store”. This store holds the information the application has access to and makes it easy to pass specific information to components that need it instead of passing state and props from a child to a parent to another child. Redux dispatches actions, which can grab information from a database, perform calculations of data in the store, update the information in the store and a variety of other things, and makes connections between the store and individual components. Middleware, like Redux-Thunk, can even be added to allow for async actions.

