# LEARN PHP WITH LARACASTS
## PHP for Beginners (2023 Edition) Laracasts

` https://www.youtube.com/playlist?list=PL3VM-unCzF8ipG50KDjnzhugceoSG3RTC `

## PHP For Beginners, Ep 3 - Your First PHP Tag
` https://www.youtube.com/watch?v=Nu-KcUO3q_U&list=PL3VM-unCzF8ipG50KDjnzhugceoSG3RTC&index=3 `
```
<?php
    echo "Hello World!";
?>
```
## PHP For Beginners, Ep 4 - Variables
` https://www.youtube.com/watch?v=twfIaZEF21k&list=PL3VM-unCzF8ipG50KDjnzhugceoSG3RTC&index=4 `

#### Semicolon

```
;
```
Php script command always end with a semicolon.

#### Concatenation

```
.
```
Concatenation is used for Combine things.

#### Variable

```
$gretting = "Hello";
```
Variable can store string or values.

#### Different ways to write variable

```
echo "$gretting everyone";
```

#### Single vs double quotes

Cannot Store variable in `single quotes`. Can Store variable in `double quotes`.

## PHP For Beginners, Ep 5 - Conditionals and Booleans
`https://www.youtube.com/watch?v=c2eThSDDwH0&list=PL3VM-unCzF8ipG50KDjnzhugceoSG3RTC&index=6`

```
<?php
    $name = "Dark Matter";
    $read = true;

    if ($read) {
        $message = "You have read $name";
    }else{
        $message = "You have Not read $name";
    }
?>
<h1>
    <?php echo $message; ?>

    // Above Code can be Write in this way. Result are same.
    <?= $message ?>
</h1>
```
