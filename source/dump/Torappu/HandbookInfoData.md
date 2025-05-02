# HandbookInfoData

**Namespace:** `Torappu`


## Fields

- `String charID`

- `String infoName`

- `Boolean isLimited`


## Methods

- `Boolean ShouldSerializeisLimited()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HandbookInfoData
{
	public String charID; // 0x10
	public String infoName; // 0x18
	public Boolean isLimited; // 0x20
	public HandBookStoryViewData[] storyTextAudio; // 0x28
	public List`1 handbookAvgList; // 0x30


	// RVA: 0x34a31b0 VA: 0x7595abb1b0
	public Boolean ShouldSerializeisLimited() { }
	// RVA: 0x34a31b8 VA: 0x7595abb1b8
	public Void .ctor() { }
}
```