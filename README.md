







```
```
```
Code Runner

C:\dev9\ts>npm install -g typescript

C:\dev9\ts>tsc --init

C:\dev9\ts>npm install -g ts-node


C:\dev9\ts>tsc index.ts

```"# typescript" 
"# typescript" 
"# typescript" 



# https://www.typescriptlang.org/docs/

# https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html




```
    let helloWorld = "Hello World";



    const user = {
        name: "Hayes",
        id: 0,
    };

    interface User {
        name: string;
        id: number;
    }

    const user: User = {
        name: "Hayes",
        id: 0,
    };





    interface User {
        name: string;
        id: number;
    }
    
    class UserAccount {
        name: string;
        id: number;
    
        constructor(name: string, id: number) {
            this.name = name;
            this.id = id;
        }
    }
    
    const user: User = new UserAccount("Murphy", 1);



    function deleteUser(user: User) {
        // ...
    }
    
    function getAdminUser(): User {
        //...
    }


    type MyBool = true | false;


    type WindowStates = "open" | "closed" | "minimized";
    type LockStates = "locked" | "unlocked";
    type PositiveOddNumbersUnderTen = 1 | 3 | 5 | 7 | 9;






```