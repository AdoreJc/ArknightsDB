# CharExtraWordData

**Namespace:** `Torappu`


## Fields

- `String wordKey`

- `String charId`

- `String voiceId`

- `String voiceText`


## Properties

- `String charWordId`


## Methods

- `String get_charWordId()`

- `String GetWordKey()`

- `String GetCharId()`

- `String GetVoiceAsset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharExtraWordData : ICharWordData
{
	private const String CHAR_WORD_ID_FORMAT; // 0x0
	private const String VOICE_ASSET_FORMAT; // 0x0
	public String wordKey; // 0x10
	public String charId; // 0x18
	public String voiceId; // 0x20
	public String voiceText; // 0x28

	public String charWordId { get; }

	// RVA: 0x33cad6c VA: 0x75959e2d6c
	public String get_charWordId() { }
	// RVA: 0x33cadd8 VA: 0x75959e2dd8
	public String GetWordKey() { }
	// RVA: 0x33cade0 VA: 0x75959e2de0
	public String GetCharId() { }
	// RVA: 0x33cade8 VA: 0x75959e2de8
	public String GetVoiceAsset() { }
	// RVA: 0x33cad7c VA: 0x75959e2d7c
	public static String GenerateCharWordId(String wordKey, String voiceId) { }
	// RVA: 0x33cae38 VA: 0x75959e2e38
	public Void .ctor() { }
}
```