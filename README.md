<h1 align="center">Hi 👽, I'm Vinayak</h1>
<h3 align="center">A passionate developer from India</h3>

<h3 align="left">Implementation:</h3>
<p align="left">
A go to way for implementing singletone

Singleton<T> : this will not keep the singleton instance alive if the scene got destroyed
```c#
public class GameManager : Singleton<GameManager>
{
    public void StartGame(){
        //..GAME START LOGIC
    }
}
```

SingletonDNDL<T> : this will keep the singleton instance alive if the scene got destroyed (DontDestroyOnLoad)
```c#
public class GameManager : SingletonDNDL<GameManager>
{
    public void StartGame(){
        //..GAME START LOGIC
    }
}
```

Calling: 
```c#
GameManager.Instance.StartGame();
```

<h3 align="left">Tip : Do not overload your project flow with singletone</h3>

![singleton_unity](https://user-images.githubusercontent.com/26487440/216897371-1b1f5df7-37f8-4a66-b719-75fa3020248d.jpeg)


</p>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://instagram.com/andrioder_vinayak_" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="andrioder_vinayak_" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://unity.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="unity" width="40" height="40"/> </a> </p>
