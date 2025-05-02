# NameCardV2CrossAppShareAdditionModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String nickName`

- `String nickNumber`

- `String uid`

- `String shareTimeDay`

- `String shareTimeSecond`

- `String nameCardSkinId`

- `Int32 nameCardSkinTmpl`

- `Boolean showUid`


## Methods

- `Void InitData()`

- `Void SetSkinId(String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2CrossAppShareAdditionModel : ICrossAppShareRemakeAdditionBaseModel, IHotfixable
{
	private const String NICK_NUMBER_FORMAT; // 0x0
	private const String UID_FORMAT; // 0x0
	private const String TIME_DAY_FORMAT; // 0x0
	private const String TIME_SECOND_FORMAT; // 0x0
	public String nickName; // 0x10
	public String nickNumber; // 0x18
	public String uid; // 0x20
	public String shareTimeDay; // 0x28
	public String shareTimeSecond; // 0x30
	public String nameCardSkinId; // 0x38
	public Int32 nameCardSkinTmpl; // 0x40
	public Boolean showUid; // 0x44
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_SetSkinId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28d0a60 VA: 0x7594ee8a60
	public Void InitData() { }
	// RVA: 0x28d0cd8 VA: 0x7594ee8cd8
	public Void SetSkinId(String nameCardSkinId, Int32 nameCardSkinTmpl) { }
	// RVA: 0x28d0d6c VA: 0x7594ee8d6c
	public Void .ctor() { }
}
```