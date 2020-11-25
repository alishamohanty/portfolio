<template>
  <footer class="Footer">
    <section class="inner-footer">
      <section class="footer-text">
        <p>
          <span>
            Feel free to say Hi !
            <a href="#" class="footer-icons">
              <font-awesome-icon :icon="['fas', 'envelope']" />
            </a>
            <br />
          </span>
        </p>
        <h4>
          You are magnificiently beautiful in your own way
        </h4>
      </section>
      <section class="footer-sociallinks">
        <ul>
          <li>
            <a href="#"><font-awesome-icon :icon="['fab', 'medium']"/></a>
          </li>
          <li>
            <a href="#"><font-awesome-icon :icon="['fab', 'twitter']"/></a>
          </li>
          <li>
            <a href="#"><font-awesome-icon :icon="['fab', 'linkedin']"/></a>
          </li>
          <li>
            <a href="#"><font-awesome-icon :icon="['fab', 'github']"/></a>
          </li>
        </ul>
        <p>Copyright &copy; {{ new Date().getFullYear() }} Alisha Mohanty</p>
      </section>
    </section>
  </footer>
</template>

<style scoped>
.Footer {
  text-align: center;
  color: #fff;
  font-family: "Source Serif Pro";
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  background: #091336;
}
.Footer .inner-footer .footer-text svg {
  height: 32px;
  width: 30px;
  color: #fbb946;
  margin-bottom: -10px;
}
.Footer .inner-footer .footer-text h4 {
  margin-top: 10px;
  font-family: "Source Serif Pro";
  text-transform: capitalize;
  font-style: normal;
  font-weight: 600;
  color: #dee0e7;
  font-size: 18px;
}
.footer-sociallinks p {
  color: #b3b5b9;
  font-family: "Source Serif Pro";
  letter-spacing: 0.8px;
  margin-top: -6px;
}
.Footer .inner-footer {
  display: flex;
  /* background: #091336; */
}
.Footer .inner-footer .footer-text p span {
  font-style: normal;
  font-weight: 500;
  letter-spacing: 0.15em;
  color: #b3b5b9;
  letter-spacing: 0.4px;
  font-size: 18px;
}
.Footer .inner-footer .footer-sociallinks {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  z-index: 999;
}
.footer-text {
  color: aliceblue;
}
.Footer .inner-footer .footer-sociallinks ul li svg {
  height: 32px;
  width: 30px;
  color: #fafafa;
}
.Footer .inner-footer .footer-sociallinks ul li:first-child {
  margin-left: 0;
}
.Footer .inner-footer .footer-text {
  display: flex;
  flex-direction: column;
}
.Footer .inner-footer .footer-sociallinks ul li {
  margin-left: 24px;
  margin-right: 0;
  width: inherit;
  opacity: 0.6;
  transition: all 0.3s ease-in-out;
}
.Footer .inner-footer .footer-sociallinks ul {
  display: flex;
  flex-direction: row;
  list-style: none;
}
@media screen and (min-width: 768px) {
  .inner-footer {
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: 40px;
    max-width: 1288px;
    margin: 0 auto;
  }
  .inner-footer .footer-text {
    align-items: flex-start;
  }
  .inner-footer {
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: 40px;
    max-width: 1288px;
    margin: 0 auto;
  }
}
@media screen and (max-width: 767px) {
  .footer-text,
  .inner-footer {
    align-items: center;
  }
  .inner-footer {
    flex-direction: column;
    padding: 24px 0;
  }
  .footer-text p {
    text-align: center;
    font-size: 10px;
    line-height: 14px;
  }
  .footer-text h4 {
    font-size: 20px;
    line-height: 28px;
    max-width: 300px;
    text-align: center;
  }
}
</style>
