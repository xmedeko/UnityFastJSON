# UnityFastJSON

Fork of [C# fastJSON](https://github.com/mgholam/fastJSON) to fix issue [#102 Feature Request: Support IL2CPP - AOT for JSON.ToObject](https://github.com/mgholam/fastJSON/issues/102). (This project will exists until the issue #102 is fixed).

So, this project fixes fastJSON to work for IL2CPP - AOT, too - for Unity3D framework and Xamarin. Just define `ENABLE_IL2CPP` symbol (Unity defines it for the IL2CPP builds).
