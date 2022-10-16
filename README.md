# SYTWC---SASS---1

ejecutar index.html

---------------------------------------------------------------------------------------

Ejercicios:

1

```ruby
$color1: #fff
$color2: #095169
$color3: #30162B


header
  background-color: #531946

.header a
  color: $color1

  &:hover
    color: $color2

.footer
  background-color: $color3
  color: $color1

  a
    color: $color2

    &:hover
      color: $color1

.feature a
  background-color: $color3
  color: #fff

  &:hover
    color: #531946

.content
  background-color: $color1
  color: #222

```
---------------------------------------------------------------------------------------
2

```ruby
.header {
  background-color: #531946;
  border-radius: 5px;
  padding: 5px 20px;

  a {
    color: #fff;

    &:hover {
      color: #095169;
    }
  }
}

.footer {
  background-color: #30162B;
  color: #fff;
  border-radius: 5px;
  padding: 5px 20px;

  a {
    color: #095169;

    &:hover {
      color: #fff;
    }
  }
}

.feature a {
  background-color: #30162B;
  color: #fff;
  border-radius: 5px;
  padding: 5px 20px;

  &:hover {
    color: #531946;
  }
}

.content {
  background-color: #fff;
  color: #222;
  border-radius: 5px;
  padding: 5px 20px;
}

```
---------------------------------------------------------------------------------------
3

```ruby
.navigation {
  float: right;

  li {
    display: inline-block;
    list-style-type: none;
    margin-left: 1.5em;
  }

  a {
    display: block;
    text-decoration: none;
  }
}

```
---------------------------------------------------------------------------------------
4

```ruby
a {
  color: #beedee;

  &:hover {
    color: #cbbebb;
  }

  &.btn {
    background: #deede6;
  }

  .btn {
    display: block;
  }
}
```
---------------------------------------------------------------------------------------
5

```ruby
header, .footer, .feature a, .content {
  border-radius: 5px;
  padding: 5px 20px;
}

```


---------------------------------------------------------------------------------------
6

```ruby
$px1: 5px
$px2: 10px

.header
  -webkit-border-radius: $px1
  -moz-border-radius: $px1
  border-radius: $px1

.footer
  -webkit-border-radius: $px2
  -moz-border-radius: $px2
  border-radius: $px2
```
