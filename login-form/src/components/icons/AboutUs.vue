<script>
  export default {
    name: "AboutUs",
  };
</script>

<template>
    <div>
      <!-- Navbar -->
      <header class="navbar">
        <div class="logo">Logo</div>
        <nav>
          <a href="#">About Us</a>
          <a href="#">FAQ</a>
          <a href="#">Feedback</a>
          <input type="text" placeholder="Search here" />
        </nav>
      </header>
  
      <!-- Main Content -->
      <main class="container">
        <h2>About Us</h2>
        <section class="about-section">
          <div class="about-content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem
              sapiente sit iste minus laboriosam consequuntur aperiam consequatur
              dolor, blanditiis corporis repudiandae accusantium suscipit enim,
              perspiciatis magnam atque excepturi sed ad.
            </p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
              ducimus minima doloremque veritatis, voluptate veniam deleniti
              delectus optio dolores aliquam ipsam ab porro quas repellat illum
              tempore ipsa architecto rem.
            </p>
          </div>
          <div class="about-image">
            <img
              src="https://tse1.mm.bing.net/th?id=OIP.HxaKqLmvfNy7CpWe7vhCagHaEM&pid=Api&P=0&h=180"
              alt="About Image 1"
            />
          </div>
        </section>
        <section class="about-section">
          <div class="about-image">
            <img
              src="https://tse3.mm.bing.net/th?id=OIP.x1-rZBc4TeWlZMA_eWVHTAHaFH&pid=Api&P=0&h=180"
              alt="About Image 2"
            />
          </div>
          <div class="about-content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat
              exercitationem vel ipsum nisi. Praesentium, perferendis magni
              suscipit commodi, necessitatibus omnis qui, at distinctio sunt
              obcaecati in blanditiis veritatis eveniet quod.
            </p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam
              accusantium ex consequuntur cum unde veniam quis quos dolores,
              doloribus officia est eum voluptatibus laborum itaque sit,
              perspiciatis earum quidem iusto.
            </p>
          </div>
        </section>
        <section class="about-section">
          <div class="about-content">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Dignissimos voluptatem saepe nostrum reiciendis sunt autem dolore
              sint explicabo, laudantium minima, a accusamus eligendi aspernatur
              suscipit magni, amet quibusdam temporibus facilis?
            </p>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
              Perferendis voluptas maiores sit eaque quis dignissimos, repellat
              praesentium veritatis tempore, accusantium pariatur illo, aperiam
              vero nemo minima dicta assumenda! Nesciunt, autem.
            </p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo
              optio soluta aliquam aperiam autem expedita sit nulla aliquid
              provident facilis nesciunt temporibus odio accusamus, est quam
              dolorum officiis alias a?
            </p>
          </div>
          <div class="about-image">
            <img
              src="https://tse2.mm.bing.net/th?id=OIP.geM5utLtuMy-vcUZ7ibs-AHaEK&pid=Api&P=0&h=180"
              alt="About Image 3"
            />
          </div>
        </section>
      </main>
  
      <!-- Footer -->
      <footer class="contact-section">
        <div class="contact-info">
          <h3>Contact Information</h3>
          <p>Address: 1234 Main Street, City, State, ZIP</p>
          <p>Phone: (123) 456-7890</p>
          <p>Email: contact@company.com</p>
        </div>
        <div class="follow-us">
          <h3>Follow Us</h3>
          <img
            src="https://tse1.mm.bing.net/th?id=OIP.fAA-1EqTinNMiq_8nz3kVAHaHa&pid=Api&P=0&h=180"
            alt="Facebook"
          />
          <img
            src="https://tse3.mm.bing.net/th?id=OIP.mTTV2N4gKfEVErWJuqtBIgHaHa&pid=Api&P=0&h=180"
            alt="Twitter"
          />
          <img
            src="https://tse1.mm.bing.net/th?id=OIP.La_4BRdJqZFXREDl9ricdgHaHa&pid=Api&P=0&h=180"
            alt="Instagram"
          />
        </div>
      </footer>
    </div>
  </template>
  
  <style scoped>
  /* Add all the CSS styles here */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
  }
  
  .container {
    width: 90%;
    margin: 0 auto;
    background-color: #ffffff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }
  
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 50px;
    background-color: #333; 
    color: #ffffff; 
    font-family: Arial, sans-serif;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); 
}

.navbar .logo {
    font-size: 24px;
    font-weight: bold;
    color: #d1d1cd;
}

.navbar nav {
    display: flex;
    align-items: center;
    gap: 20px;
}

.navbar nav a {
    text-decoration: none;
    color: #ffffff;
    font-size: 16px;
    transition: color 0.3s ease-in-out;
    padding: 5px 10px;
    border-radius: 3px;
}

.navbar nav a:hover {
    color: #e7d4d4; 
    background-color: rgba(255, 255, 255, 0.1); 
}

.navbar nav input[type="text"] {
    padding: 7px 15px;
    border: none;
    border-radius: 3px;
    font-size: 14px;
    outline: none;
    color: #000000; 
    background-color: #f8f9fa; 
    transition: box-shadow 0.3s ease-in-out;
}

.navbar nav input[type="text"]:focus {
    box-shadow: 0 0 5px #f1e05a; 
}

main {
    padding: 20px 0;
}

h2 {
    text-align: center;
    margin-bottom: 30px;
}

.about-section {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 30px;
}
.about-content {
    flex: 1;
    min-width: 300px;
}
.about-content p {
    line-height: 1.6;
}
.about-image {
    flex: 1;
    min-width: 300px;
    }
.about-image img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
.contact-section {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
    gap: 20px;
}
.contact-info {
    flex: 1;
    min-width: 300px;
}
.follow-us {
    flex: 1;
    min-width: 300px;
    display: flex;
    gap: 10px;
}
.follow-us img {
    width: 40px;
    height: 40px;
}
footer.contact-section {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

footer .contact-info,
footer .follow-us {
    flex: 1;
    min-width: 300px;
}

footer h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

footer p {
    margin: 5px 0;
    font-size: 14px;
    line-height: 1.5;
}

footer .follow-us {
    text-align: left;
}

footer .follow-us img {
    width: 40px;
    height: 40px;
    margin: 5px;
    cursor: pointer;
    transition: transform 0.2s;
}

footer .follow-us img:hover {
    transform: scale(1.1);
}
</style>
  