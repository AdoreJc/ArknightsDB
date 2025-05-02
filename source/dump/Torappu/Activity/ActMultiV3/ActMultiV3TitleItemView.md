# ActMultiV3TitleItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _titleText`

- `GameObject _lockedGo`

- `RectTransform _trackpointHolder`

- `GameObject _newTrackPoint`

- `Boolean m_inited`

- `Int32 m_cachedPageIndex`

- `Boolean m_cachedIsBack`

- `Boolean m_cachedSelected`

- `UIStateFinder m_stateFinder`

- `GameObject m_newTrackObj`


## Methods

- `Void Render(Param, Boolean)`

- `Void OnClickItem()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TitleItemView : MonoBehaviour, IHotfixable
{
	private Text _titleText; // 0x18
	private GameObject _lockedGo; // 0x20
	private RectTransform _trackpointHolder; // 0x28
	private GameObject _newTrackPoint; // 0x30
	private Boolean m_inited; // 0x38
	private Int32 m_cachedPageIndex; // 0x3c
	private Boolean m_cachedIsBack; // 0x40
	private Boolean m_cachedSelected; // 0x41
	private UIStateFinder m_stateFinder; // 0x48
	private GameObject m_newTrackObj; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickItem; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x311d908 VA: 0x7595735908
	public Void Render(Param param, Boolean isSelected) { }
	// RVA: 0x311db14 VA: 0x7595735b14
	public Void OnClickItem() { }
	// RVA: 0x311da2c VA: 0x7595735a2c
	private Void _InitIfNot() { }
	// RVA: 0x311dc28 VA: 0x7595735c28
	public Void .ctor() { }
}
```