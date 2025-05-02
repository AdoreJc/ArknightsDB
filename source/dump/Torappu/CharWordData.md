# CharWordData

**Namespace:** `Torappu`


## Fields

- `String charWordId`

- `String wordKey`

- `String charId`

- `String voiceId`

- `String voiceText`

- `String voiceTitle`

- `Int32 voiceIndex`

- `CharWordVoiceType voiceType`

- `DataUnlockType unlockType`

- `String lockDescription`

- `CharWordShowType placeType`

- `String voiceAsset`


## Methods

- `String GetWordKey()`

- `String GetCharId()`

- `String GetVoiceAsset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharWordData : ICharWordData
{
	public static readonly HashSet`1 ILLUST_SHOW_TYPES; // 0x0
	public String charWordId; // 0x10
	public String wordKey; // 0x18
	public String charId; // 0x20
	public String voiceId; // 0x28
	public String voiceText; // 0x30
	public String voiceTitle; // 0x38
	public Int32 voiceIndex; // 0x40
	public CharWordVoiceType voiceType; // 0x44
	public DataUnlockType unlockType; // 0x48
	public List`1 unlockParam; // 0x50
	public String lockDescription; // 0x58
	public CharWordShowType placeType; // 0x60
	public String voiceAsset; // 0x68


	// RVA: 0x33caadc VA: 0x75959e2adc
	public String GetWordKey() { }
	// RVA: 0x33caae4 VA: 0x75959e2ae4
	public String GetCharId() { }
	// RVA: 0x33caaec VA: 0x75959e2aec
	public String GetVoiceAsset() { }
	// RVA: 0x33caaf4 VA: 0x75959e2af4
	public Void .ctor() { }
	// RVA: 0x33cab80 VA: 0x75959e2b80
	private static Void .cctor() { }
}
```