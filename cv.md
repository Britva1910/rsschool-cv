# __Ivan Lashuk__
 
#### Frontend-developer
 
E-MAIL: ivan.lashuk2013@gmail.com	|  	
 
## About me
I wish to work as a front-end developer and to develop in this area. My current work  calls for permanent concentration,flexibility and readiness to study all the time because of the necessity to verify and estimate big amounts of new information in different life spheres, and to make quick decisions.
 
 
## Skils
 
* JavaScript/HTML/CSS (in the process of learning);
* Git (basic level), SCSS;
* VScode.
## Сode example:
```
const MODERN_ACTIVITY = 15;
const HALF_LIFE_PERIOD = 5730;

module.exports = function dateSample(sampleActivity) {
    let nam = Number(sampleActivity);
    if (typeof sampleActivity != 'string') {
        return false;
    } else if (Number(sampleActivity) <= 0 || Number(sampleActivity) > 15) {
        return false;
    } else if (isNaN(nam) || nam == 0) {
        return false;
    } else {
        const k = (0.693 / HALF_LIFE_PERIOD);
        let time = Math.log(MODERN_ACTIVITY / sampleActivity) / k;
        return Math.ceil(time);
    }
};
```
## Experience:
At the moment I have no working experience as a front-end developer. I have completed HTML Academy training courses on HTML and CSS and Code Basics JavaSсript.
 
## Education:
2006-2011 Belarusian State University, bachelor’s degree in law.
 
English: elementary level (in the process of learning).