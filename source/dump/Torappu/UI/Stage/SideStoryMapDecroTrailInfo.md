# SideStoryMapDecroTrailInfo

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UICommonTrackPoint _uiTrackContainer`

- `Text _currentStar`

- `Text _maxStar`

- `TrackPointViewProperty m_trailAvailProperty`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderInfo(String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SideStoryMapDecroTrailInfo : MonoBehaviour, IHotfixable
{
	private UICommonTrackPoint _uiTrackContainer; // 0x18
	private Text _currentStar; // 0x20
	private Text _maxStar; // 0x28
	private TrackPointViewProperty m_trailAvailProperty; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f1730c VA: 0x759552f30c
	private Void _InitIfNot() { }
	// RVA: 0x2f168f0 VA: 0x759552e8f0
	public Void RenderInfo(String retroId) { }
	// RVA: 0x2f173fc VA: 0x759552f3fc
	public Void OnClick() { }
	// RVA: 0x2f17504 VA: 0x759552f504
	public Void .ctor() { }
}
```