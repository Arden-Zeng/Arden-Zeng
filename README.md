Hey there! 👋

I'm Arden, a software engineer skilled in building React/TypeScript applications. I'm currently studying CS at the University of Waterloo while lending a hand to a stealth startup in Silicon Valley.

Prev: Software Engineering Intern @ [Bluescape](https://www.bluescape.com/)

I don't use Github as often as I should, so this profile might change over the next few weeks as I slowly sift through my hard drives and find some things I'm proud of :)

Stuff I've built for myself / internships:
- Client-side React Routing Library (With hooks!)
- SSR/ISR/ISG Serverless React Framework
- (In Progress / Prototyping) React Global State Management Library (Using `Object.defineProperty()` to dynamically create getters and setters at runtime + useSyncExternalStore)
  - Example Usage
  ```ts
  /***
  "$" is the global state object, but we use the "getter" to subscribe the
  current component to the requested property only.
  i.e. changes to $.anotherGlobalValue do not cause a re-render in this component.
  ***/
  function reactFunctionalComponent() {
    const myGlobalState = $.someGlobalValue;
    return <>{myGlobalState}</>
  }
  ```


<!--**Arden-Zeng/Arden-Zeng** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.-->
