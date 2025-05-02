# GachaSceneParam

**Namespace:** `Torappu.Gacha`


## Fields

- `PlayMode playMode`

- `Input input`

- `String nextScene`

- `Options nextOptions`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class GachaSceneParam : ISceneParam
{
	public PlayMode playMode; // 0x10
	public Input input; // 0x18
	public String nextScene; // 0x78
	public Options nextOptions; // 0x80
	public Action`1 endCb; // 0xa8


	// RVA: 0x35c69c8 VA: 0x7595bde9c8
	public Void .ctor() { }
}
```