# Act12sideJunkdealerView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideUISpineCharController _uiSpineController`

- `Text _dialogText`

- `String m_activityId`


## Methods

- `Void InitView(String)`

- `Void PlayJunkDealerDialog(Int32, Boolean)`

- `Void _RenderDialog(String)`

- `Void _RenderUiSpineFacial(RecycleAnimationState)`

- `RecycleDialogData _TryGenRecycleDialog(Int32, Boolean)`

- `RecycleDialogType _GenRecycleType(Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideJunkdealerView : MonoBehaviour, IHotfixable
{
	private Act12sideUISpineCharController _uiSpineController; // 0x18
	private Text _dialogText; // 0x20
	private String m_activityId; // 0x28
	private Dictionary`2 m_dialogDict; // 0x30
	private static DelegateBridge __Hotfix0_InitView; // 0x0
	private static DelegateBridge __Hotfix0_PlayJunkDealerDialog; // 0x8
	private static DelegateBridge __Hotfix0__RenderDialog; // 0x10
	private static DelegateBridge __Hotfix0__RenderUiSpineFacial; // 0x18
	private static DelegateBridge __Hotfix0__TryGenRecycleDialog; // 0x20
	private static DelegateBridge __Hotfix0__GenRecycleType; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x34636a0 VA: 0x7595a7b6a0
	public Void InitView(String activityId) { }
	// RVA: 0x34637fc VA: 0x7595a7b7fc
	public Void PlayJunkDealerDialog(Int32 recyclePoint, Boolean isGacha) { }
	// RVA: 0x3463a54 VA: 0x7595a7ba54
	private Void _RenderDialog(String content) { }
	// RVA: 0x3463ae8 VA: 0x7595a7bae8
	private Void _RenderUiSpineFacial(RecycleAnimationState animationState) { }
	// RVA: 0x34638b8 VA: 0x7595a7b8b8
	private RecycleDialogData _TryGenRecycleDialog(Int32 recyclePoints, Boolean isGacha) { }
	// RVA: 0x3463ba0 VA: 0x7595a7bba0
	private RecycleDialogType _GenRecycleType(Int32 recyclePoints, Boolean isGacha) { }
	// RVA: 0x3463c8c VA: 0x7595a7bc8c
	public Void .ctor() { }
}
```