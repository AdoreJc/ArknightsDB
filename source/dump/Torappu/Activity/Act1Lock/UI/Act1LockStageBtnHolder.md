# Act1LockStageBtnHolder

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Act1LockStageBtn _prefab`

- `RectTransform _container`

- `String _stageId`

- `CanvasGroup _canvasGroup`

- `Vector2 originPosition`

- `Vector2 advancedPosition`

- `Act1LockStageBtn m_button`

- `Int32 m_appliedPrefabSign`


## Properties

- `RectTransform buttonContainer`

- `Act1LockStageBtn button`

- `String stageId`


## Methods

- `RectTransform get_buttonContainer()`

- `Void SetupIfNeeded(Act1LockStageBtn, Boolean)`

- `Void _SetHolderStatus(Boolean)`

- `Act1LockStageBtn get_button()`

- `String get_stageId()`

- `Void TryPlayAnimation(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockStageBtnHolder : MonoBehaviour, IHotfixable
{
	private Act1LockStageBtn _prefab; // 0x18
	private RectTransform _container; // 0x20
	private String _stageId; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	public Vector2 originPosition; // 0x38
	public Vector2 advancedPosition; // 0x40
	private Act1LockStageBtn m_button; // 0x48
	private Int32 m_appliedPrefabSign; // 0x50
	private const Single ALPHA_ZERO; // 0x0
	private const Single ALPHA_ONE; // 0x0
	private const Single TWEENER_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_get_buttonContainer; // 0x0
	private static DelegateBridge __Hotfix0_SetupIfNeeded; // 0x8
	private static DelegateBridge __Hotfix0__SetHolderStatus; // 0x10
	private static DelegateBridge __Hotfix0_get_button; // 0x18
	private static DelegateBridge __Hotfix0_get_stageId; // 0x20
	private static DelegateBridge __Hotfix0_TryPlayAnimation; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected RectTransform buttonContainer { get; }
	public Act1LockStageBtn button { get; }
	public String stageId { get; }

	// RVA: 0x33d4398 VA: 0x75959ec398
	protected RectTransform get_buttonContainer() { }
	// RVA: 0x33cf028 VA: 0x75959e7028
	public Void SetupIfNeeded(Act1LockStageBtn defaultPrefab, Boolean anyInterLockUnlocked) { }
	// RVA: 0x33d4450 VA: 0x75959ec450
	private Void _SetHolderStatus(Boolean interLockUnlocked) { }
	// RVA: 0x33cf300 VA: 0x75959e7300
	public Act1LockStageBtn get_button() { }
	// RVA: 0x33ceee4 VA: 0x75959e6ee4
	public String get_stageId() { }
	// RVA: 0x33cf720 VA: 0x75959e7720
	public Void TryPlayAnimation(Boolean isFinalFirst, Boolean isInterlockFirst) { }
	// RVA: 0x33d45fc VA: 0x75959ec5fc
	public Void .ctor() { }
}
```