# InfoShareVisitor

**Namespace:** ` `


## Fields

- `VisitorInfo m_info`


## Properties

- `Sprite icon`

- `String userId`

- `String nickName`

- `String nickNumber`

- `String comment`

- `Int32 level`

- `Boolean online`

- `DateTime lastLoginTime`

- `Int32 creditReward`

- `AvatarInfo avatarInfo`

- `PlayerNameCardSkin nameCardSkin`


## Methods

- `Sprite get_icon()`

- `String get_userId()`

- `String get_nickName()`

- `String get_nickNumber()`

- `String get_comment()`

- `Int32 get_level()`

- `Boolean get_online()`

- `DateTime get_lastLoginTime()`

- `Boolean HasCard(Int32)`

- `Int32 get_creditReward()`

- `AvatarInfo get_avatarInfo()`

- `PlayerNameCardSkin get_nameCardSkin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InfoShareVisitor : IPeer, IHotfixable
{
	private VisitorInfo m_info; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_icon; // 0x8
	private static DelegateBridge __Hotfix0_get_userId; // 0x10
	private static DelegateBridge __Hotfix0_get_nickName; // 0x18
	private static DelegateBridge __Hotfix0_get_nickNumber; // 0x20
	private static DelegateBridge __Hotfix0_get_comment; // 0x28
	private static DelegateBridge __Hotfix0_get_level; // 0x30
	private static DelegateBridge __Hotfix0_get_online; // 0x38
	private static DelegateBridge __Hotfix0_get_lastLoginTime; // 0x40
	private static DelegateBridge __Hotfix0_HasCard; // 0x48
	private static DelegateBridge __Hotfix0_get_creditReward; // 0x50
	private static DelegateBridge __Hotfix0_get_avatarInfo; // 0x58
	private static DelegateBridge __Hotfix0_get_nameCardSkin; // 0x60

	public Sprite icon { get; }
	public String userId { get; }
	public String nickName { get; }
	public String nickNumber { get; }
	public String comment { get; }
	public Int32 level { get; }
	public Boolean online { get; }
	public DateTime lastLoginTime { get; }
	public Int32 creditReward { get; }
	public AvatarInfo avatarInfo { get; }
	public PlayerNameCardSkin nameCardSkin { get; }

	// RVA: 0x3de6ebc VA: 0x75963feebc
	public Void .ctor(VisitorInfo info) { }
	// RVA: 0x3de6f50 VA: 0x75963fef50
	public Sprite get_icon() { }
	// RVA: 0x3de6fb4 VA: 0x75963fefb4
	public String get_userId() { }
	// RVA: 0x3de7034 VA: 0x75963ff034
	public String get_nickName() { }
	// RVA: 0x3de70a8 VA: 0x75963ff0a8
	public String get_nickNumber() { }
	// RVA: 0x3de711c VA: 0x75963ff11c
	public String get_comment() { }
	// RVA: 0x3de7190 VA: 0x75963ff190
	public Int32 get_level() { }
	// RVA: 0x3de7204 VA: 0x75963ff204
	public Boolean get_online() { }
	// RVA: 0x3de7268 VA: 0x75963ff268
	public DateTime get_lastLoginTime() { }
	// RVA: 0x3de7308 VA: 0x75963ff308
	public Boolean HasCard(Int32 category) { }
	// RVA: 0x3de7380 VA: 0x75963ff380
	public Int32 get_creditReward() { }
	// RVA: 0x3de73e4 VA: 0x75963ff3e4
	public AvatarInfo get_avatarInfo() { }
	// RVA: 0x3de7458 VA: 0x75963ff458
	public PlayerNameCardSkin get_nameCardSkin() { }
}
```