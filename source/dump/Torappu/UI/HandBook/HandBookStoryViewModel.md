# HandBookStoryViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String storyTitle`

- `Boolean unlockFlag`

- `Boolean initFlag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookStoryViewModel
{
	public List`1 stories; // 0x10
	public String storyTitle; // 0x18
	public Boolean unlockFlag; // 0x20
	public Boolean initFlag; // 0x21


	// RVA: 0x2ebe7fc VA: 0x75954d67fc
	public static HandBookStoryViewModel ConvertFromData(HandBookStoryViewData data, CharQuery charQuery) { }
	// RVA: 0x2ec084c VA: 0x75954d884c
	public Void .ctor() { }
}
```