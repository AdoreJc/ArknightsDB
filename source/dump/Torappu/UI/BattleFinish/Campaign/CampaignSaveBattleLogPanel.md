# CampaignSaveBattleLogPanel

**Namespace:** `Torappu.UI.BattleFinish.Campaign`


## Fields

- `Toggle _toggle`

- `Text _versionText`

- `Text _savetimeText`

- `Text _remainingCostText`

- `Text _playTimeText`

- `Text _lifePointText`

- `Text _missedEnemiesCntText`

- `Text _killedEnemiesCntText`

- `RectTransform _newHint`

- `EasyInstancePool _charCardPool`


## Properties

- `Boolean isOn`

- `Boolean interactable`


## Methods

- `Boolean get_isOn()`

- `Void set_isOn(Boolean)`

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `Void Render(BattleLog, Boolean)`

- `String _FormatVersionStr(UInt32)`

- `String _FormatPlayTimeStr(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish.Campaign
public class CampaignSaveBattleLogPanel : MonoBehaviour
{
	private Toggle _toggle; // 0x18
	private Text _versionText; // 0x20
	private Text _savetimeText; // 0x28
	private Text _remainingCostText; // 0x30
	private Text _playTimeText; // 0x38
	private Text _lifePointText; // 0x40
	private Text _missedEnemiesCntText; // 0x48
	private Text _killedEnemiesCntText; // 0x50
	private RectTransform _newHint; // 0x58
	private EasyInstancePool _charCardPool; // 0x60
	private List`1 m_playerChars; // 0x68

	public Boolean isOn { get; set; }
	public Boolean interactable { get; set; }

	// RVA: 0x2e97504 VA: 0x75954af504
	public Boolean get_isOn() { }
	// RVA: 0x2e97520 VA: 0x75954af520
	public Void set_isOn(Boolean value) { }
	// RVA: 0x2e97540 VA: 0x75954af540
	public Boolean get_interactable() { }
	// RVA: 0x2e969dc VA: 0x75954ae9dc
	public Void set_interactable(Boolean value) { }
	// RVA: 0x2e966d8 VA: 0x75954ae6d8
	public Void Render(BattleLog log, Boolean isNew) { }
	// RVA: 0x2e976f4 VA: 0x75954af6f4
	private static Void _LoadPlayerCharsToShow(List`1 squadInJournal, ref List`1 squadToShow) { }
	// RVA: 0x2e9755c VA: 0x75954af55c
	private String _FormatVersionStr(UInt32 version) { }
	// RVA: 0x2e97618 VA: 0x75954af618
	private String _FormatPlayTimeStr(Single playTime) { }
	// RVA: 0x2e97978 VA: 0x75954af978
	public Void .ctor() { }
}
```