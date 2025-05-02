# CrisisV2EntryTempButtonView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIStateFinder m_stateFinder`

- `Text _name`

- `Text _code`

- `Text _remainTime`

- `Image _zoneIcon`

- `Button _canvasGroupPanel`

- `GameObject _notOpenPart`

- `GameObject _openPart`

- `GameObject _availPart`

- `GameObject _inRewardTimePart`

- `GameObject _outRewardTimePart`

- `GameObject _allResPart`

- `Graphic _imgLogoBg`

- `TempPart m_cacheViewModel`


## Methods

- `Void Render(TempPart)`

- `Void OnClickTemp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2EntryTempButtonView : MonoBehaviour, IHotfixable
{
	private UIStateFinder m_stateFinder; // 0x18
	private Text _name; // 0x28
	private Text _code; // 0x30
	private Text _remainTime; // 0x38
	private Image _zoneIcon; // 0x40
	private Button _canvasGroupPanel; // 0x48
	private GameObject _notOpenPart; // 0x50
	private GameObject _openPart; // 0x58
	private GameObject _availPart; // 0x60
	private GameObject _inRewardTimePart; // 0x68
	private GameObject _outRewardTimePart; // 0x70
	private GameObject _allResPart; // 0x78
	private Graphic _imgLogoBg; // 0x80
	private TempPart m_cacheViewModel; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickTemp; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2bfbbb0 VA: 0x7595213bb0
	public Void Render(TempPart tempPart) { }
	// RVA: 0x2bfbef8 VA: 0x7595213ef8
	public Void OnClickTemp() { }
	// RVA: 0x2bfc000 VA: 0x7595214000
	public Void .ctor() { }
}
```