## Three ways to center div

1. Position absolute
2. Flexbox
3. Grid

### General code

```
*{
    margin: 0; padding: 0;
    box-sizing: border-box;
}
.parent{
    background: #222831;
    width: 100vw;
    height: 100vh;
}
.child{
    background:#00ADB5;
    width: 60vw;
    height: 60vh;
}
```

### 1. Position absolute
```
.parent{
    background: #222831;
    width: 100vw;
    height: 100vh;
}

.child{
    background:#00ADB5;
    width: 60vw;
    height: 60vh;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}

```

### 2. Flexbox
```
.parent{
background: #222831;
width: 100vw;
height: 100vh;
display:flex;
justify-content: center;
align-items: center;
}
.child{
    background:#00ADB5;
    width: 60vw;
    height: 60vh;
}
```

### 3. Grid
```
.parent{
    background: #222831;
    width: 100vw;
    height: 100vh;
    display: grid;
    place-items: center;
    }
.child{
    background:#00ADB5;
    width: 60vw;
    height: 60vh;
    }
```

## Conclusion
- Conclusion: Third way is the fastest way to do center.

Note: Design is responsive...