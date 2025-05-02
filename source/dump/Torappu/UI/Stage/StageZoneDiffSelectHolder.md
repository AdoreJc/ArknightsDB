# StageZoneDiffSelectHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneDiffSelectObj _selectObj`

- `AnimationWrapper _animWrapper`

- `SimpleLayoutContent _content`

- `GameObject _addedZoneRewardBtn`

- `UnityEvent onAchieveRewardZoneAction`

- `UIDiffGroupEvent selectDiffAction`

- `UnityEvent onOpenDetailClick`

- `Single m_isHideState`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `Tween m_cacheTween`


## Methods

- `Void _InitIfNot()`

- `Void Render(ZoneViewModel)`

- `Void OnStateChange(Boolean)`

- `Void OnOpenDetailClick()`

- `Void OnAchieveRewardZoneAction()`

- `Single <OnStateChange>b__17_0()`

- `Void <OnStateChange>b__17_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneDiffSelectHolder : MonoBehaviour, IHotfixable
{
	private StageZoneDiffSelectObj _selectObj; // 0x18
	private GameObject[] _transList; // 0x20
	private AnimationWrapper _animWrapper; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private GameObject _addedZoneRewardBtn; // 0x38
	public UnityEvent onAchieveRewardZoneAction; // 0x40
	public UIDiffGroupEvent selectDiffAction; // 0x48
	public UnityEvent onOpenDetailClick; // 0x50
	private const String PARAM_ANIM; // 0x0
	private Single m_isHideState; // 0x58
	private List`1 m_diffObjList; // 0x60
	private Adapter m_adapter; // 0x68
	private Boolean m_isInited; // 0x70
	private Tween m_cacheTween; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnStateChange; // 0x10
	private static DelegateBridge __Hotfix0_OnOpenDetailClick; // 0x18
	private static DelegateBridge __Hotfix0_OnAchieveRewardZoneAction; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2f8e10c VA: 0x75955a610c
	private Void _InitIfNot() { }
	// RVA: 0x2f8e260 VA: 0x75955a6260
	public Void Render(ZoneViewModel zoneViewModel) { }
	// RVA: 0x2f8e468 VA: 0x75955a6468
	public Void OnStateChange(Boolean isHide) { }
	// RVA: 0x2f8e870 VA: 0x75955a6870
	public Void OnOpenDetailClick() { }
	// RVA: 0x2f8e8ec VA: 0x75955a68ec
	public Void OnAchieveRewardZoneAction() { }
	// RVA: 0x2f8e968 VA: 0x75955a6968
	public Void .ctor() { }
	// RVA: 0x2f8e9d8 VA: 0x75955a69d8
	private Single <OnStateChange>b__17_0() { }
	// RVA: 0x2f8e9e0 VA: 0x75955a69e0
	private Void <OnStateChange>b__17_1(Single val) { }
}
```