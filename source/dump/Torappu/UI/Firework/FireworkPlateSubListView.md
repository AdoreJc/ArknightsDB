# FireworkPlateSubListView

**Namespace:** `Torappu.UI.Firework`


## Fields

- `UIAnimationLocation _animShow`

- `UIAnimationLocation _animSwitch`

- `SimpleLayoutContent _plateList`

- `Boolean m_inited`

- `UISwitchTween m_showTween`

- `UISwitchTween m_lengthSwitchTween`

- `FireworkPlateGroupModel m_cachedGroupModel`

- `FireworkPlateGroupViewStyle m_cachedStyle`

- `String m_cachedPlateGroupId`

- `Adapter m_adapter`

- `PreviewingStatus m_cachedPreviewingStatus`

- `Boolean m_isNewGroup`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(FireworkPlateGroupModel, FireworkPlateGroupViewStyle)`

- `Void _TutorialOnlyRaiseAVGSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateSubListView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animShow; // 0x18
	private UIAnimationLocation _animSwitch; // 0x28
	private SimpleLayoutContent _plateList; // 0x38
	private Boolean m_inited; // 0x40
	private UISwitchTween m_showTween; // 0x48
	private UISwitchTween m_lengthSwitchTween; // 0x50
	private FireworkPlateGroupModel m_cachedGroupModel; // 0x58
	private FireworkPlateGroupViewStyle m_cachedStyle; // 0x60
	private String m_cachedPlateGroupId; // 0x68
	private Adapter m_adapter; // 0x70
	private PreviewingStatus m_cachedPreviewingStatus; // 0x78
	private Boolean m_isNewGroup; // 0x7c
	private UIStateFinder m_stateFinder; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__TutorialOnlyRaiseAVGSignal; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28f2524 VA: 0x7594f0a524
	private Void _InitIfNot() { }
	// RVA: 0x28f05cc VA: 0x7594f085cc
	public Void Render(FireworkPlateGroupModel groupModel, FireworkPlateGroupViewStyle style) { }
	// RVA: 0x28f2810 VA: 0x7594f0a810
	private Void _TutorialOnlyRaiseAVGSignal() { }
	// RVA: 0x28f2a08 VA: 0x7594f0aa08
	public Void .ctor() { }
}
```