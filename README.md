# homework № 3
:root {
  --primary-color: #2e2f42;
  --secondary-color: #434455;
  --accent-color: #4d5ae5;
  --light-color: #f4f4fd;
  --dark-color: #333;
  --white-color: #fff;
  --font-primary: 'Roboto', sans-serif;
  --font-secondary: 'Raleway', sans-serif;
}

body {
  font-family: var(--font-primary);
  color: var(--secondary-color);
  background-color: var(--white-color);
}

h1, h2, h3, h4, h5, h6, p {
  margin: 0;
  padding: 0;
  margin-bottom: 8px;
}

ul, ol {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
  display: inline-block;
  margin-bottom: 16px;
}

.logo {
  font-family: var(--font-secondary);
  font-weight: 700;
  font-size: 18px;
  line-height: 1.17;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: var(--accent-color);
}

.header-logo {
  padding: 24px 0;
  margin-right: 76px;
}

.header-logo .logo-part {
  color: var(--primary-color);
}

.footer-logo .logo-part {
  color: var(--light-color);
}

.tixt {
  font-family: var(--font-primary);
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  letter-spacing: 0.02em;
  color: var(--light-color);
}

.nav-list {
  display: flex;
  align-items: center;
  gap: 40px;
}

.nav-link {
  font-family: var(--font-primary);
  padding: 24px 0;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.5;
  letter-spacing: 0.02em;
  color: var(--primary-color);
}

.nav-link:hover, .nav-link:focus, .contacts-link:hover, .contacts-link:focus {
  color: #404bbf;
}

.contacts {
  font-style: normal;
  margin-left: auto;
  margin: 24px 0;
}

.contacts-list {
  display: flex;
  align-items: center;
  gap: 40px;
}

.contacts-item {
  margin-bottom: 8px;
}

.contacts-link {
  font-family: var(--font-primary);
  font-weight: 400;
  font-size: 16px;
  line-height: 1.5;
  letter-spacing: 0.02em;
  color: var(--light-color);
}

.page-footer {
  padding: 60px 0;
  background-color: var(--primary-color);
  color: var(--light-color);
}

.page-section {
  background-color: var(--primary-color);
  padding: 188px 0;
}

.page-header {
  border-bottom: 1px solid #e7e9fc;
}

.container {
  width: 100%;
  max-width: 1158px;
  padding-left: 15px;
  padding-right: 15px;
  margin: 0 auto;
}

.header-container {
  display: flex;
  align-items: center;
}

.header-nav {
  display: flex;
  align-items: center;
}

.typog {
  font-family: var(--font-primary);
  font-weight: 700;
  font-size: 56px;
  line-height: 1.07;
  letter-spacing: 0.02em;
  text-align: center;
  color: var(--white-color);
  max-width: 496px;
}

.text-primary {
  font-family: var(--font-primary);
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  letter-spacing: 0.02em;
  color: var(--light-color);
}

.button {
  font-family: var(--font-primary);
  font-weight: 500;
  font-size: 16px;
  line-height: 150%;
  letter-spacing: 0.04em;
  color: var(--white-color);
  cursor: pointer;
  background-color: var(--accent-color);
  display: block;
  min-width: 169px;
  height: 56px;
  border: none;
  border-radius: 4px;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.button:hover, .button:focus {
  background-color: #404bbf;
}

.item-title {
  font-family: var(--font-primary);
  font-weight: 500;
  font-size: 20px;
  line-height: 120%;
  letter-spacing: 0.02em;
  color: var(--primary-color);
  text-align: center;
  margin-bottom: 8px;
}

.first-item-title {
  color: var(--secondary-color);
  font-size: 24px;
  font-weight: 700;
}

.item-text {
  font-family: var(--font-primary);
  font-weight: 400;
  font-size: 16px;
  line-height: 1.5;
  letter-spacing: 0.02em;
  color: var(--secondary-color);
  text-align: center;
}

.team-section {
  background-color: var(--light-color);
  padding: 120px 0;
}

.team-list {
  display: flex;
  gap: 24px;
}

.team {
  font-family: var(--font-primary);
  font-weight: 700;
  font-size: 36px;
  line-height: 111%;
  letter-spacing: 0.02em;
  color: var(--primary-color);
  text-transform: capitalize;
  text-align: center;
  margin-bottom: 72px;
}

.team-li {
  background-color: var(--white-color);
  width: calc((100% - 72px)/4);
}

.team-li:first-child {
  border-radius: 0 0 4px 4px;
}

.content {
  background: var(--white-color);
}

.employee-name {
  background-color: var(--white-color);
  font-family: var(--font-primary);
  font-weight: 500;
  font-size: 20px;
  line-height: 120%;
  letter-spacing: 0.02em;
  text-transform: capitalize;
  color: var(--primary-color);
  text-align: center;
  margin-bottom: 8px;
}

.employee-position {
  font-family: var(--font-primary);
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  letter-spacing: 0.02em;
  text-transform: capitalize;
  color: var(--secondary-color);
  text-align: center;
}

.portfolio-section {
  padding: 120px 0;
}

.section-title {
  font-family: var(--font-primary);
  font-weight: 700;
  font-size: 36px;
  line-height: 111%;
  letter-spacing: 0.02em;
  text-align: center;
  color: var(--primary-color);
  background-color: var(--white-color);
  text-transform: capitalize;
  margin-bottom: 72px;
}

.portfolio-list {
  display: flex;
  flex-wrap: wrap;
  gap: 24px;
}

.portfolio-item {
  width: calc((100% - 48px) / 3);
}

.portfolio-content {
  padding: 32px 16px;
  border: 1px solid #e7e9fc;
  border-top: none;
}

.portfolio-title {
  font-family: var(--font-primary);
  font-weight: 500;
  font-size: 20px;
  line-height: 120%;
  letter-spacing: 0.02em;
  color: var(--primary-color);
  background-color: var(--white-color);
  margin-bottom: 8px;
}

.employee-position {
  font-family: var(--font-primary);
  font-weight: 400;
  font-size: 16px;
  line-height: 150%;
  letter-spacing: 0.02em;
  color: var(--secondary-color);
  text-align: center;
}

.sec-heder, .big-title {
  font-weight: 500;
  font-size: 56px;
  line-height: 1.07;
  letter-spacing: 0.02em;
  text-align: center;
  color: var(--white-color);
}

img {
  display: block;
}

.title-section {
  padding: 120px 0;
}

.title-item {
  background-color: var(--white-color);
  width: calc((100% - 48px) / 3);
  transition: box-shadow 0.3s ease;
}

.title-item:hover {
  box-shadow: 0px 1px 6px rgba(46, 47, 66, 0.08), 0px 1px 1px rgba(46, 47, 66, 0.16), 0px 2px 1px rgba(46, 47, 66, 0.08);
}

.title-content {
  padding: 32px 16px;
