# MedalDetailHolderSingleton

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalListAlreadyGetItemDetailView _detailView`

- `MedalListNoGetItemDetailView _noGetDetailView`

- `Transform _container`

- `GameObject _activeHolder`

- `UIStringEvent m_dismissAct`

- `MedalListAlreadyGetItemDetailView m_detailView`

- `MedalListNoGetItemDetailView m_noGetDetailView`

- `Boolean m_isInited`

- `Boolean m_lockedFlag`

- `Boolean m_isShow`


## Methods

- `Void _InitIfNot()`

- `Void OnOpenDetail(RectTransform, MedalCommonViewModel, UIStringEvent)`

- `Void _Close(String)`

- `Boolean IsShown()`

- `Void OnClickDetail(String)`

- `Void Close()`

- `Void OpenAlready(RectTransform, MedalCommonViewModel)`

- `Void OpenNotGet(RectTransform, MedalCommonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalDetailHolderSingleton : PageSingleComponent
{
	private MedalListAlreadyGetItemDetailView _detailView; // 0x20
	private MedalListNoGetItemDetailView _noGetDetailView; // 0x28
	private Transform _container; // 0x30
	private GameObject _activeHolder; // 0x38
	private UIStringEvent m_dismissAct; // 0x40
	private MedalListAlreadyGetItemDetailView m_detailView; // 0x48
	private MedalListNoGetItemDetailView m_noGetDetailView; // 0x50
	private Boolean m_isInited; // 0x58
	private Boolean m_lockedFlag; // 0x59
	private Boolean m_isShow; // 0x5a
	private static DelegateBridge __Hotfix0_LockClick; // 0x0
	private static DelegateBridge __Hotfix0_GetUnlockFlag; // 0x8
	private static DelegateBridge __Hotfix0_UnlockClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnOpenDetailStatic; // 0x20
	private static DelegateBridge __Hotfix0_OnOpenDetail; // 0x28
	private static DelegateBridge __Hotfix0__Close; // 0x30
	private static DelegateBridge __Hotfix0_CloseStatic; // 0x38
	private static DelegateBridge __Hotfix0_IsShow; // 0x40
	private static DelegateBridge __Hotfix0_IsShown; // 0x48
	private static DelegateBridge __Hotfix0_OnClickDetail; // 0x50
	private static DelegateBridge __Hotfix0_Close; // 0x58
	private static DelegateBridge __Hotfix0_OpenAlready; // 0x60
	private static DelegateBridge __Hotfix0_OpenNotGet; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x279ee94 VA: 0x7594db6e94
	public static Void LockClick() { }
	// RVA: 0x279ef78 VA: 0x7594db6f78
	public static Boolean GetUnlockFlag() { }
	// RVA: 0x279f068 VA: 0x7594db7068
	public static Void UnlockClick() { }
	// RVA: 0x279f148 VA: 0x7594db7148
	private Void _InitIfNot() { }
	// RVA: 0x279f33c VA: 0x7594db733c
	public static Void OnOpenDetailStatic(RectTransform rect, MedalCommonViewModel viewModel, UIStringEvent dismissAct) { }
	// RVA: 0x279f45c VA: 0x7594db745c
	public Void OnOpenDetail(RectTransform rect, MedalCommonViewModel viewModel, UIStringEvent dismissAct) { }
	// RVA: 0x279f7c8 VA: 0x7594db77c8
	private Void _Close(String targetMedalId) { }
	// RVA: 0x2791b1c VA: 0x7594da9b1c
	public static Void CloseStatic() { }
	// RVA: 0x2791a2c VA: 0x7594da9a2c
	public static Boolean IsShow() { }
	// RVA: 0x27935cc VA: 0x7594dab5cc
	public Boolean IsShown() { }
	// RVA: 0x279f8f0 VA: 0x7594db78f0
	public Void OnClickDetail(String medalId) { }
	// RVA: 0x2793634 VA: 0x7594dab634
	public Void Close() { }
	// RVA: 0x279f5b8 VA: 0x7594db75b8
	public Void OpenAlready(RectTransform rect, MedalCommonViewModel viewModel) { }
	// RVA: 0x279f6bc VA: 0x7594db76bc
	public Void OpenNotGet(RectTransform rect, MedalCommonViewModel viewModel) { }
	// RVA: 0x279fc00 VA: 0x7594db7c00
	public Void .ctor() { }
}
```