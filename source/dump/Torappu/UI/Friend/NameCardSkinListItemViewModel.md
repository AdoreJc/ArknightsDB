# NameCardSkinListItemViewModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String skinId`

- `Int32 skinTmpl`

- `String nickName`

- `String nickNameId`

- `String uid`

- `AvatarInfo avatarInfo`

- `Boolean isSkinUnlock`

- `Boolean canChangeTmpl`


## Methods

- `Void LoadDataForSkinList(String)`

- `Void LoadDataForSkinTmplList(String, Int32)`

- `Void UpdateData()`

- `Void _LoadCommon()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinListItemViewModel : IHotfixable
{
	public String skinId; // 0x10
	public Int32 skinTmpl; // 0x18
	public String nickName; // 0x20
	public String nickNameId; // 0x28
	public String uid; // 0x30
	public AvatarInfo avatarInfo; // 0x38
	public Boolean isSkinUnlock; // 0x40
	public Boolean canChangeTmpl; // 0x41
	private static DelegateBridge __Hotfix0_LoadDataForSkinList; // 0x0
	private static DelegateBridge __Hotfix0_LoadDataForSkinTmplList; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge __Hotfix0__LoadCommon; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28bec48 VA: 0x7594ed6c48
	public Void LoadDataForSkinList(String skinId) { }
	// RVA: 0x28bef20 VA: 0x7594ed6f20
	public Void LoadDataForSkinTmplList(String skinId, Int32 skinTmpl) { }
	// RVA: 0x28bee00 VA: 0x7594ed6e00
	public Void UpdateData() { }
	// RVA: 0x28bed18 VA: 0x7594ed6d18
	private Void _LoadCommon() { }
	// RVA: 0x28befbc VA: 0x7594ed6fbc
	public Void .ctor() { }
}
```