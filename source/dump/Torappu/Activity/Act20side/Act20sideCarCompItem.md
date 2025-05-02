# Act20sideCarCompItem

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `GameObject _selectPart`

- `UIStringEvent compSelectEvent`

- `UIAtlasImage _rarityFrameImg`

- `UIAtlasObject _rarityFrameHolder`

- `Text _name`

- `Image _itemIcon`

- `UICommonTrackPoint _commonTrackPoint`

- `TrackPointViewProperty m_updatedTrackPointProperty`

- `CartCompViewModel m_viewModel`


## Methods

- `Void OnClick()`

- `Void _UpdateTrackPoint(String)`

- `Void RenderViewModel(CartCompViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarCompItem : MonoBehaviour, IHotfixable
{
	private GameObject _selectPart; // 0x18
	public UIStringEvent compSelectEvent; // 0x20
	private UIAtlasImage _rarityFrameImg; // 0x28
	private UIAtlasObject _rarityFrameHolder; // 0x30
	private Text _name; // 0x38
	private Image _itemIcon; // 0x40
	private UICommonTrackPoint _commonTrackPoint; // 0x48
	private TrackPointViewProperty m_updatedTrackPointProperty; // 0x50
	private CartCompViewModel m_viewModel; // 0x58
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0__UpdateTrackPoint; // 0x8
	private static DelegateBridge __Hotfix0_RenderViewModel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x32edc80 VA: 0x7595905c80
	public Void OnClick() { }
	// RVA: 0x32edd1c VA: 0x7595905d1c
	private Void _UpdateTrackPoint(String compId) { }
	// RVA: 0x32ede24 VA: 0x7595905e24
	public Void RenderViewModel(CartCompViewModel viewModel) { }
	// RVA: 0x32ee094 VA: 0x7595906094
	public Void .ctor() { }
}
```