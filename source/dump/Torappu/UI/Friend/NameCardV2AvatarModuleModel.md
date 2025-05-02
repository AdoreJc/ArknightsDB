# NameCardV2AvatarModuleModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String nickName`

- `String nickNameId`

- `Int32 level`

- `String uid`

- `AvatarInfo avatarInfo`

- `Boolean isSelf`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2AvatarModuleModel : NameCardV2ModuleBaseModel
{
	public String nickName; // 0x38
	public String nickNameId; // 0x40
	public Int32 level; // 0x48
	public String uid; // 0x50
	public AvatarInfo avatarInfo; // 0x58
	public Boolean isSelf; // 0x60
	private static DelegateBridge __Hotfix0_OnLoadFriendData; // 0x0
	private static DelegateBridge __Hotfix0_OnLoadSelfData; // 0x8
	private static DelegateBridge __Hotfix0_OnRefreshSelfData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28c3278 VA: 0x7594edb278
	protected override Void OnLoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c3344 VA: 0x7594edb344
	protected override Void OnLoadSelfData() { }
	// RVA: 0x28c3448 VA: 0x7594edb448
	protected override Void OnRefreshSelfData() { }
	// RVA: 0x28c34f0 VA: 0x7594edb4f0
	public Void .ctor() { }
}
```