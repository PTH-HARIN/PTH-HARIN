```JavaScript
'use strict';

/!-[ About and Infomation ]-!/

class Harin {};

class Attributes extends Harin {
    constructor() {
        super();
        this.contact = () => ({
            email: 'phungtuanhai03@gmail.com',
            facebook: 'https://www.facebook.com/HARIN.MIKA1',
            instagram: 'https://www.instagram.com/pth_tth2506'
        });

        this.coding = () => ({
            programmingLanguages: {
                expert: ['JavaScript'],
                learning: ['HTML/CSS']
            },
            dataSupports: {
                framework: ['Node.JS'],
                databases: ['MongoDB', 'SQLite'],
                deploy: ['Hosting'],
                package: ['NPM'],
            },
            IDEs: ['VSCODE', 'Replit']
        });

        this.life = () => ({
            name: ['Phùng Tuấn Hải'],
            username: ['PTH', 'Harin'],
            age: 'xx',
            address: ['127.0.0.1'],
            location: ['localhost, vietnamese'],
            occupation: ['Newbie Study Code'],
            careerObjective: ['Trở thành một lập trình viên full-stack (FE)'],
            hobbies: ['Chơi game', 'Nghe nhạc', 'Xem phim', 'Code'],
            operatingSystem: ['Linux, VPS'],
            spokenLanguages: ['Vietnamese', 'English'],
            webSite: 'https://harin.onrender.com'
        });

        this.contributes = () => ({
            thanks: ['Võ Viết Duy Khiêm']
        });
    }
}
```
