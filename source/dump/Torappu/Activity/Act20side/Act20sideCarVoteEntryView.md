# Act20sideCarVoteEntryView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Text _hotValue`

- `Text _dailyHotValue`

- `Text _leftJudgeTimes`

- `Text _playerName`

- `Text _playerNickNumber`

- `Text _playerLevel`

- `GameObject _hotValNoData`

- `GameObject _dailyValNoData`

- `Transform _avatarContainer`

- `Single _avatarViewScale`

- `Act20sideCarObject _carPrefab`

- `Transform _carContainer`

- `GameObject _carMask`

- `Single _carViewScale`

- `Boolean m_isInited`

- `Act20sideCarObject m_carView`

- `PlayerAvatarView m_avatarView`

- `Int32 m_cachedDailyHotVal`

- `Tween m_cachedDailyHotValTween`


## Methods

- `Void _InitIfNot()`

- `Void _ApplyAvatar(AvatarInfo)`

- `Void _TweenDailyHotValIfNecessary(Int32)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarVoteEntryView : DataBinder`1
{
	private const Single DAILY_HOT_VAL_TWEEN_DURATION; // 0x0
	private Text _hotValue; // 0x20
	private Text _dailyHotValue; // 0x28
	private Text _leftJudgeTimes; // 0x30
	private Text _playerName; // 0x38
	private Text _playerNickNumber; // 0x40
	private Text _playerLevel; // 0x48
	private GameObject _hotValNoData; // 0x50
	private GameObject _dailyValNoData; // 0x58
	private Transform _avatarContainer; // 0x60
	private Single _avatarViewScale; // 0x68
	private Act20sideCarObject _carPrefab; // 0x70
	private Transform _carContainer; // 0x78
	private GameObject _carMask; // 0x80
	private Single _carViewScale; // 0x88
	private Boolean m_isInited; // 0x8c
	private Act20sideCarObject m_carView; // 0x90
	private PlayerAvatarView m_avatarView; // 0x98
	private Int32 m_cachedDailyHotVal; // 0xa0
	private Tween m_cachedDailyHotValTween; // 0xa8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ApplyAvatar; // 0x10
	private static DelegateBridge __Hotfix0__TweenDailyHotValIfNecessary; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32fb990 VA: 0x7595913990
	public override Void OnValueChanged(Act20sideCarVoteEntryProperty property) { }
	// RVA: 0x32fbc90 VA: 0x7595913c90
	private Void _InitIfNot() { }
	// RVA: 0x32fc3d8 VA: 0x75959143d8
	private Void _ApplyAvatar(AvatarInfo avatarInfo) { }
	// RVA: 0x32fbf48 VA: 0x7595913f48
	private Void _TweenDailyHotValIfNecessary(Int32 dailyHotVal) { }
	// RVA: 0x32fc5fc VA: 0x75959145fc
	private Void OnDestroy() { }
	// RVA: 0x32fc67c VA: 0x759591467c
	public Void .ctor() { }
}
```