# CharacterInfoHolderViewButtons

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `TwoStateToggle _starMarkToggle`

- `GameObject _handbookButton`

- `UnityEvent _onStateClick`

- `UICommonTrackPoint _handbookTrackPoint`

- `TrackPointViewProperty handbookInfoTrackProp`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnStateChangeClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoHolderViewButtons : DataBinder`1
{
	private TwoStateToggle _starMarkToggle; // 0x20
	private GameObject _handbookButton; // 0x28
	private UnityEvent _onStateClick; // 0x30
	private UICommonTrackPoint _handbookTrackPoint; // 0x38
	public TrackPointViewProperty handbookInfoTrackProp; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnStateChangeClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d688c8 VA: 0x75953808c8
	private Void _InitIfNot() { }
	// RVA: 0x2d68970 VA: 0x7595380970
	public override Void OnValueChanged(CharInfoGroupProperty property) { }
	// RVA: 0x2d68ac4 VA: 0x7595380ac4
	public Void OnStateChangeClick() { }
	// RVA: 0x2d68b40 VA: 0x7595380b40
	public Void .ctor() { }
}
```