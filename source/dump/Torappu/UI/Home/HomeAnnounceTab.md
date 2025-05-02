# HomeAnnounceTab

**Namespace:** `Torappu.UI.Home`


## Fields

- `TwoStateToggle _twoStateToggle`

- `Int32 announceIndex`

- `AnnounceSinglePageData cacheData`

- `Text _day`

- `Text _month`

- `Text _title`

- `Text _dayB`

- `Text _monthB`

- `Text _titleB`

- `GameObject _newTag`


## Methods

- `Void InitData(AnnounceSinglePageData)`

- `Void SetOnSelect(Int32)`

- `Void AnnounceSelectClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeAnnounceTab : MonoBehaviour
{
	private TwoStateToggle _twoStateToggle; // 0x18
	public Action`1 announceClick; // 0x20
	public Int32 announceIndex; // 0x28
	public AnnounceSinglePageData cacheData; // 0x30
	private Text _day; // 0x38
	private Text _month; // 0x40
	private Text _title; // 0x48
	private Text _dayB; // 0x50
	private Text _monthB; // 0x58
	private Text _titleB; // 0x60
	private GameObject _newTag; // 0x68


	// RVA: 0x28343f0 VA: 0x7594e4c3f0
	public Void InitData(AnnounceSinglePageData data) { }
	// RVA: 0x283461c VA: 0x7594e4c61c
	public Void SetOnSelect(Int32 index) { }
	// RVA: 0x2834700 VA: 0x7594e4c700
	public Void AnnounceSelectClick() { }
	// RVA: 0x2834720 VA: 0x7594e4c720
	public Void .ctor() { }
}
```