# SandboxV2DungeonReadArchiveItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _animLocation`

- `Text _txtDayTitle`

- `Text _txtDayCount`

- `RectTransform _transSeasonAngle`

- `SimpleLayoutContent _apListContent`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `SandboxV2DungeonReadArchiveItemModel m_model`

- `ApItemListAdapter m_adapter`

- `AnimationSwitchTween m_tween`


## Methods

- `Void Render(SandboxV2DungeonReadArchiveItemModel)`

- `Void SetTweenShow(Boolean)`

- `Void _InitIfNot()`

- `Void OnArchiveItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonReadArchiveItemView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animLocation; // 0x18
	private Text _txtDayTitle; // 0x28
	private Text _txtDayCount; // 0x30
	private RectTransform _transSeasonAngle; // 0x38
	private SimpleLayoutContent _apListContent; // 0x40
	private Boolean m_isInited; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private SandboxV2DungeonReadArchiveItemModel m_model; // 0x60
	private ApItemListAdapter m_adapter; // 0x68
	private AnimationSwitchTween m_tween; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetTweenShow; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnArchiveItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x252a4fc VA: 0x7594b424fc
	public Void Render(SandboxV2DungeonReadArchiveItemModel model) { }
	// RVA: 0x252a788 VA: 0x7594b42788
	public Void SetTweenShow(Boolean isShow) { }
	// RVA: 0x252a884 VA: 0x7594b42884
	private Void _InitIfNot() { }
	// RVA: 0x252abd8 VA: 0x7594b42bd8
	public Void OnArchiveItemClick() { }
	// RVA: 0x252acdc VA: 0x7594b42cdc
	public Void .ctor() { }
}
```