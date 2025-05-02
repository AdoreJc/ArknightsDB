# Act20sideCarVoteEntryViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Int32 m_score`

- `Int32 m_dailyScore`

- `Int32 m_judgeCount`

- `AvatarInfo m_avatarInfo`

- `String m_playerName`

- `String m_nickName`

- `Int32 m_level`

- `Cart m_playerCart`

- `Boolean m_hasJoinedExhibition`


## Properties

- `Int32 score`

- `Int32 dailyScore`

- `Int32 judgeCount`

- `String playerName`

- `String nickName`

- `AvatarInfo avatarInfo`

- `Cart playerCart`

- `Boolean hasJoinedExhibition`

- `Int32 level`


## Methods

- `Int32 get_score()`

- `Int32 get_dailyScore()`

- `Int32 get_judgeCount()`

- `String get_playerName()`

- `String get_nickName()`

- `AvatarInfo get_avatarInfo()`

- `Cart get_playerCart()`

- `Boolean get_hasJoinedExhibition()`

- `Int32 get_level()`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarVoteEntryViewModel : IHotfixable
{
	private Int32 m_score; // 0x10
	private Int32 m_dailyScore; // 0x14
	private Int32 m_judgeCount; // 0x18
	private AvatarInfo m_avatarInfo; // 0x20
	private String m_playerName; // 0x28
	private String m_nickName; // 0x30
	private Int32 m_level; // 0x38
	private Cart m_playerCart; // 0x40
	private Boolean m_hasJoinedExhibition; // 0x48
	private static DelegateBridge __Hotfix0_get_score; // 0x0
	private static DelegateBridge __Hotfix0_get_dailyScore; // 0x8
	private static DelegateBridge __Hotfix0_get_judgeCount; // 0x10
	private static DelegateBridge __Hotfix0_get_playerName; // 0x18
	private static DelegateBridge __Hotfix0_get_nickName; // 0x20
	private static DelegateBridge __Hotfix0_get_avatarInfo; // 0x28
	private static DelegateBridge __Hotfix0_get_playerCart; // 0x30
	private static DelegateBridge __Hotfix0_get_hasJoinedExhibition; // 0x38
	private static DelegateBridge __Hotfix0_get_level; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 score { get; }
	public Int32 dailyScore { get; }
	public Int32 judgeCount { get; }
	public String playerName { get; }
	public String nickName { get; }
	public AvatarInfo avatarInfo { get; }
	public Cart playerCart { get; }
	public Boolean hasJoinedExhibition { get; }
	public Int32 level { get; }

	// RVA: 0x32fbe10 VA: 0x7595913e10
	public Int32 get_score() { }
	// RVA: 0x32fbee0 VA: 0x7595913ee0
	public Int32 get_dailyScore() { }
	// RVA: 0x32fc308 VA: 0x7595914308
	public Int32 get_judgeCount() { }
	// RVA: 0x32fc1d0 VA: 0x75959141d0
	public String get_playerName() { }
	// RVA: 0x32fc238 VA: 0x7595914238
	public String get_nickName() { }
	// RVA: 0x32fc370 VA: 0x7595914370
	public AvatarInfo get_avatarInfo() { }
	// RVA: 0x32fc58c VA: 0x759591458c
	public Cart get_playerCart() { }
	// RVA: 0x32fbe78 VA: 0x7595913e78
	public Boolean get_hasJoinedExhibition() { }
	// RVA: 0x32fc2a0 VA: 0x75959142a0
	public Int32 get_level() { }
	// RVA: 0x32f3e88 VA: 0x759590be88
	public Void LoadData(String actId) { }
	// RVA: 0x330271c VA: 0x759591a71c
	public Void .ctor() { }
}
```