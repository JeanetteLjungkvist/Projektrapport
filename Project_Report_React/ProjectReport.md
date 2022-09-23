# React Project Report

![](2022-09-23-16-09-27.png)

## API
In our group we decided to build a webshop where we sold coding classes.
We did not use an existing API and instead created our own database.

```
var courseData = [
  {
    id: 1,
    name: "JavaScript",
    price: 1000,
    instructor: "Jahirul Haq",
    image: "https://i.ibb.co/0jHqtM0/javascript.png",
  },
```

## Hooks

We used hooks in a couple of different places in our code. We used both 'useState' and 'useEffect'. We used a useEffect in order to change the title of the document so the you can se what page you are on in the browser.

```
useEffect(() => {
    document.title = "About Us";
  }, []);
```

![](2022-09-23-16-40-49.png)

We used a useState hook in our Shop.jsx component.

```
const [course] = useState(courseData);
  const [cart, setCart] = useState([]);

  const handleCourse = (course) => {
    const newCart = [...cart, course];
    setCart(newCart);
  };
```

## Props

## SPA

Our page qualify as a SPA. Our webpage uses only one html page and with the use of routing and different components we have built that index.html page gets rewrittet every time you go to a new page.

![](2022-09-23-17-00-18.png)

```
  <BrowserRouter>
    <Routes>
      <Route path="/" element={<App />} />
      <Route path="about" element={<AboutUs />} />
      <Route path="products" element={<Products />} />
      <Route path="registration" element={<Registration />} />
    </Routes>
  </BrowserRouter>
```

## Responsive/Component library
In order for our webpage to be responsive we used a couple different methods. For some components, for example the navbar and the cards displaying our courses, we used react bootstrap. On other components we used flex box and media queries, for example on the footer and the about us page.

```
import { Button, Card, Container, Stack } from "react-bootstrap";
```
```
.about-container {
  display: flex;
}

.about-text-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 100%;
  text-align: center;
  padding-left: 80px;
  padding-right: 80px;
}
```
```
 @media screen and (max-width: 820px) {
  .footer-links {
    padding-top: 2rem;
  }

  .footer-link-wrapper {
    flex-direction: column;
  }
} 
```


















