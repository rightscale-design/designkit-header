# Designkit Header

## Install

```bash
npm install designkit-header --save
```

## Usage

```html
<header class="header-default header-skin sans">
  <div class="header-brand"><a href="/"><img src="https://cdn.rawgit.com/rightscale/design-kit/master/media/logos/gov-logo.svg" alt="RightScale Governance"/></a></div>
  <div class="header-nav">
    <nav><a href="/">Mark one</a><a href="/">Mark two</a><a href="/">Mark three</a></nav>
  </div>
</header>
```

## The CSS

```css
.header-default {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 46px;
  background-color: #0069CC;
}

.header-default.header-skin {
  background-color: #076CCA;
  background-image: linear-gradient(#076CCA, #065BAC);
  border-bottom: 1px solid rgba(0, 0, 0, 0.2);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.2), inset 0 -2px 0 rgba(0, 0, 0, 0.08);
}

.header-default .header-brand {
  float: left;
  padding: 0 15px;
  overflow: hidden;
  color: #fff;
}

.header-default .header-brand a {
  display: block;
  float: left;
  height: 100%;
  padding: 12px 0 9px;
}

.header-default .header-brand img {
  height: 100%;
}

.header-default .header-nav {
  float: right;
  font-size: 13px;
}

.header-default .header-nav a {
  display: block;
  float: left;
  height: 100%;
  padding: .8rem .8rem .8rem;
  font-weight: 700;
  color: #fff;
  text-decoration: none;
  cursor: pointer;
  transition: all .1s;
}

.header-default .header-nav a:hover {
  background-color: rgba(0, 0, 0, 0.1);
}
```

## Author

Jason Melgoza

## License

MIT
