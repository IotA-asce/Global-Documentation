# java: clearing console lines

## clearing out the whole console

    the use of the expression **\033[H\033\K** in the print line helps solve this case

```java
public void ClearScreen(){
    System.out.println("\033[H\033[K");
}

```

## clearing out the previous line 

    the use of the expression **\033[A\033[K** in the print line helps solve this case

```java
public void ClearScreen(){
    System.out.println("\033[A\033[K");
}
```

# java: adding sound to your code

    a single beep can be achieved by using the

```java
    Toolkit.getDefaultToolkit().beep();

```