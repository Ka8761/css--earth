# css--earth

<title>Document</title> <style> body { width: 100vw; height: 100vw; margin: 0; display: flex; position: fixed; background-color: #123; }
#container {
    width: 80vw;
    height: 80vw;
    margin: auto;
    border-radius: 50%;
    background-color: navy;
    box-shadow: 0 0 20px white, inset 0 0 5px white;
}

#ring-1,
#ring-2 {
    width: 80vw;
    height: 40vw;
    margin: 20vw 0;
    position: absolute;
    border: 20px solid white;
    border-top-width: 10px;
    border-radius: 50%;
    box-sizing: border-box;
    transform: rotate(-30deg);
}

#atom {
    width: 50vw;
    height: 50vw;
    margin: 15vw;
    position: absolute;
    border: 5px solid navy;
    border-radius: 50%;
    box-sizing: border-box;
    background-color: aqua;
    box-shadow: inset 0 0 20px navy;
}

#ring-2 {
    border-top-color: transparent;
   border-bottom-width: 20px;
}
</style
