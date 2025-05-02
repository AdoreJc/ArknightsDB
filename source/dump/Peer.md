# Peer

**Namespace:** ` `


## Fields

- `FriendDataWithNameCard m_info`

- `Int32 m_sendReward`

- `String m_comment`


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
private class Peer : IPeer, IHotfixable
{
	private FriendDataWithNameCard m_info; // 0x10
	private Int32 m_sendReward; // 0x18
	private String m_comment; // 0x20
	private List`1 m_hasCard; // 0x28
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

	// RVA: 0x3de65e4 VA: 0x75963fe5e4
	public Void .ctor(FriendDataWithNameCard info, String comment, Int32 sendReward) { }
	// RVA: 0x3de67a0 VA: 0x75963fe7a0
	public Sprite get_icon() { }
	// RVA: 0x3de5430 VA: 0x75963fd430
	public String get_userId() { }
	// RVA: 0x3de6804 VA: 0x75963fe804
	public String get_nickName() { }
	// RVA: 0x3de6890 VA: 0x75963fe890
	public String get_nickNumber() { }
	// RVA: 0x3de6934 VA: 0x75963fe934
	public String get_comment() { }
	// RVA: 0x3de699c VA: 0x75963fe99c
	public Int32 get_level() { }
	// RVA: 0x3de6a14 VA: 0x75963fea14
	public Boolean get_online() { }
	// RVA: 0x3de6ad0 VA: 0x75963fead0
	public DateTime get_lastLoginTime() { }
	// RVA: 0x3de6b48 VA: 0x75963feb48
	public Boolean HasCard(Int32 category) { }
	// RVA: 0x3de6be8 VA: 0x75963febe8
	public Int32 get_creditReward() { }
	// RVA: 0x3de6c50 VA: 0x75963fec50
	public AvatarInfo get_avatarInfo() { }
	// RVA: 0x3de6cc8 VA: 0x75963fecc8
	public PlayerNameCardSkin get_nameCardSkin() { }
}
```