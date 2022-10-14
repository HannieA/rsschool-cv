# Hanna Anishyna

### **cellphone:** +1 650 660 43 26

### **email:** ann.986@gmail.com

## About me

I've decided to change my career totally and build strong skills in front end development.
I think my abilities to create quality content and logical approach to task completion are useful for developer.
I enjoy working on projects making convinient, beautiful and useful apps for user's experience.

## Skills

- HTML & CSS
- Java Script
- React
- Git $ Github
- Bootstrap framework
- Axios HTTP Client

## Portfolio

[Dictionary App](https://github.com/HannieA/dictionary-react)

[Weather App](https://github.com/HannieA/weather-JS)

_Code example:_

```
function handlePexel(response) {
    setPhotos(response.data.photos);
  }

  function search(event) {
    event.preventDefault();
    let apiUrl = `https://api.dictionaryapi.dev/api/v2/entries/en/${value}`;
    axios.get(apiUrl).then(showResponse);

    let pexelUrl = `https://api.pexels.com/v1/search?query=${value}&per_page=6`;
    let pexelKey = "563492ad6f91700001000001beaf3ef208ec42f6be971b2544ea2e6a";
    axios
      .get(pexelUrl, {
        headers: { Authorization: `Bearer ${pexelKey}` },
      })
      .then(handlePexel);
  }

  function handleValue(event) {
    setValue(event.target.value);
  }
```

## Education

- SheCodes Coding school
- Freecodecamp

## English

I'm living in the USA now, so I practice English every day. I've been learning the language since school and keep doing it now.
