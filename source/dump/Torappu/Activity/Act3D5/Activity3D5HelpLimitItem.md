# Activity3D5HelpLimitItem

**Namespace:** `Torappu.Activity.Act3D5`


## Fields

- `Sprite _complete`

- `Sprite _requirement`

- `Image _flagIcon`

- `Image _itemBG`

- `Text _desc`

- `Image _prgBG`

- `Text _prgCntLabel`

- `Slider _prg`

- `Text _statusLabel`

- `Text _rewardCntLabel`

- `Transform _rewardIconRoot`

- `GameObject _gotMark`

- `Boolean m_finish`

- `Int32 m_sortId`


## Properties

- `Boolean finish`

- `Int32 sortId`


## Methods

- `Void Refresh(MissionData)`

- `Boolean get_finish()`

- `Int32 get_sortId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D5
internal class Activity3D5HelpLimitItem : MonoBehaviour, IHotfixable
{
	private Sprite _complete; // 0x18
	private Sprite _requirement; // 0x20
	private Image _flagIcon; // 0x28
	private Image _itemBG; // 0x30
	private Text _desc; // 0x38
	private Image _prgBG; // 0x40
	private Text _prgCntLabel; // 0x48
	private Slider _prg; // 0x50
	private Text _statusLabel; // 0x58
	private Text _rewardCntLabel; // 0x60
	private Transform _rewardIconRoot; // 0x68
	private GameObject _gotMark; // 0x70
	private Boolean m_finish; // 0x78
	private Int32 m_sortId; // 0x7c
	private static DelegateBridge __Hotfix0_Refresh; // 0x0
	private static DelegateBridge __Hotfix0_get_finish; // 0x8
	private static DelegateBridge __Hotfix0_get_sortId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean finish { get; }
	public Int32 sortId { get; }

	// RVA: 0x322600c VA: 0x759583e00c
	public Void Refresh(MissionData missionData) { }
	// RVA: 0x3226864 VA: 0x759583e864
	public Boolean get_finish() { }
	// RVA: 0x32268cc VA: 0x759583e8cc
	public Int32 get_sortId() { }
	// RVA: 0x3226934 VA: 0x759583e934
	public Void .ctor() { }
}
```