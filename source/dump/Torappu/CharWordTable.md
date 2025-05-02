# CharWordTable

**Namespace:** `Torappu`


## Fields

- `VoiceLangType defaultLangType`

- `CharWordShowType playVoiceRange`


## Methods

- `Boolean ShouldSerializenewTagList()`

- `Boolean ShouldSerializestartTimeWithTypeDict()`

- `Boolean ShouldSerializedisplayGroupTypeList()`

- `Boolean ShouldSerializedisplayTypeList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharWordTable
{
	public Dictionary`2 charWords; // 0x10
	public Dictionary`2 charExtraWords; // 0x18
	public Dictionary`2 voiceLangDict; // 0x20
	public VoiceLangType defaultLangType; // 0x28
	public List`1 newTagList; // 0x30
	public Dictionary`2 voiceLangTypeDict; // 0x38
	public Dictionary`2 voiceLangGroupTypeDict; // 0x40
	public Dictionary`2 charDefaultTypeDict; // 0x48
	public Dictionary`2 startTimeWithTypeDict; // 0x50
	public List`1 displayGroupTypeList; // 0x58
	public List`1 displayTypeList; // 0x60
	public CharWordShowType playVoiceRange; // 0x68
	public Dictionary`2 fesVoiceData; // 0x70
	public Dictionary`2 fesVoiceWeight; // 0x78
	public Dictionary`2 extraVoiceConfigData; // 0x80


	// RVA: 0x33ca7a0 VA: 0x75959e27a0
	public Boolean ShouldSerializenewTagList() { }
	// RVA: 0x33ca7f4 VA: 0x75959e27f4
	public Boolean ShouldSerializestartTimeWithTypeDict() { }
	// RVA: 0x33ca848 VA: 0x75959e2848
	public Boolean ShouldSerializedisplayGroupTypeList() { }
	// RVA: 0x33ca89c VA: 0x75959e289c
	public Boolean ShouldSerializedisplayTypeList() { }
	// RVA: 0x33ca8f0 VA: 0x75959e28f0
	public Void .ctor() { }
}
```