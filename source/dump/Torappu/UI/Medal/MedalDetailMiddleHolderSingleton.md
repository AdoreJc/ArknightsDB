# MedalDetailMiddleHolderSingleton

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalListAlreadyGetItemDetailView _detailView`

- `MedalListNoGetItemDetailView _noGetDetailView`

- `Transform _container`

- `GameObject _activeHolder`

- `UIRenderTextureImage _blurImage`

- `CanvasGroup _canvasGroup`

- `Action m_dismissAct`

- `MedalListAlreadyGetItemDetailView m_detailView`

- `MedalListNoGetItemDetailView m_noGetDetailView`

- `Boolean m_isInited`

- `Boolean m_isShow`

- `Tween m_cacheTween`


## Methods

- `Void _InitIfNot()`

- `Void OnOpenDetail(MedalCommonViewModel)`

- `Void Close()`

- `Void OpenAlready(MedalCommonViewModel)`

- `Void OpenNotGet(MedalCommonViewModel)`

- `Single <OnOpenDetail>b__14_0()`

- `Void <OnOpenDetail>b__14_1(Single)`

- `Void <OnOpenDetail>b__14_2()`

- `Single <Close>b__17_0()`

- `Void <Close>b__17_1(Single)`

- `Void <Close>b__17_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalDetailMiddleHolderSingleton : PageSingleComponent, IHotfixable
{
	private MedalListAlreadyGetItemDetailView _detailView; // 0x20
	private MedalListNoGetItemDetailView _noGetDetailView; // 0x28
	private Transform _container; // 0x30
	private GameObject _activeHolder; // 0x38
	private UIRenderTextureImage _blurImage; // 0x40
	private CanvasGroup _canvasGroup; // 0x48
	private Action m_dismissAct; // 0x50
	private MedalListAlreadyGetItemDetailView m_detailView; // 0x58
	private MedalListNoGetItemDetailView m_noGetDetailView; // 0x60
	private Boolean m_isInited; // 0x68
	private Boolean m_isShow; // 0x69
	private Tween m_cacheTween; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnOpenDetailStatic; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenDetail; // 0x10
	private static DelegateBridge __Hotfix0_CloseStatic; // 0x18
	private static DelegateBridge __Hotfix0_IsShow; // 0x20
	private static DelegateBridge __Hotfix0_Close; // 0x28
	private static DelegateBridge __Hotfix0_OpenAlready; // 0x30
	private static DelegateBridge __Hotfix0_OpenNotGet; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2799510 VA: 0x7594db1510
	private Void _InitIfNot() { }
	// RVA: 0x2797a48 VA: 0x7594dafa48
	public static Void OnOpenDetailStatic(MedalCommonViewModel viewModel) { }
	// RVA: 0x279962c VA: 0x7594db162c
	public Void OnOpenDetail(MedalCommonViewModel viewModel) { }
	// RVA: 0x2791cf8 VA: 0x7594da9cf8
	public static Void CloseStatic() { }
	// RVA: 0x2791c08 VA: 0x7594da9c08
	public static Boolean IsShow() { }
	// RVA: 0x2799a60 VA: 0x7594db1a60
	public Void Close() { }
	// RVA: 0x27998c0 VA: 0x7594db18c0
	public Void OpenAlready(MedalCommonViewModel viewModel) { }
	// RVA: 0x279998c VA: 0x7594db198c
	public Void OpenNotGet(MedalCommonViewModel viewModel) { }
	// RVA: 0x279a5ec VA: 0x7594db25ec
	public Void .ctor() { }
	// RVA: 0x279a65c VA: 0x7594db265c
	private Single <OnOpenDetail>b__14_0() { }
	// RVA: 0x279a678 VA: 0x7594db2678
	private Void <OnOpenDetail>b__14_1(Single val) { }
	// RVA: 0x279a694 VA: 0x7594db2694
	private Void <OnOpenDetail>b__14_2() { }
	// RVA: 0x279a6b4 VA: 0x7594db26b4
	private Single <Close>b__17_0() { }
	// RVA: 0x279a6d0 VA: 0x7594db26d0
	private Void <Close>b__17_1(Single val) { }
	// RVA: 0x279a6ec VA: 0x7594db26ec
	private Void <Close>b__17_2() { }
}
```