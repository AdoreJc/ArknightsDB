# BattleUIBridge

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_inited`

- `Coroutine m_ctrlSetUpWaitCoroutine`

- `PagePluginCtrl m_pagePluginCtrl`


## Methods

- `Boolean ShowCustomDialog(DynDialogParam, OptionType)`

- `Void _OpenActivityPage(Object)`

- `Void _OnInitCallback(Object)`

- `Void _SetupPageCtrlIfExist()`

- `IEnumerator _SetUpWhenUICameraControllerReady()`

- `Boolean _IsCameraLoading()`

- `Void _SetUpPageCtrlImpl()`

- `Void _OnOpenUIPage(Object)`

- `Void _OpenPage(String, UIPageOption)`

- `Void _OnBattleCtrlDispose(Object)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleUIBridge : SingletonWithMonoHost`2, IDisposable
{
	private Boolean m_inited; // 0x10
	private Coroutine m_ctrlSetUpWaitCoroutine; // 0x18
	private PagePluginCtrl m_pagePluginCtrl; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ShowCustomDialog; // 0x8
	private static DelegateBridge __Hotfix0__OpenActivityPage; // 0x10
	private static DelegateBridge __Hotfix0__OnInitCallback; // 0x18
	private static DelegateBridge __Hotfix0__SetupPageCtrlIfExist; // 0x20
	private static DelegateBridge __Hotfix0__SetUpWhenUICameraControllerReady; // 0x28
	private static DelegateBridge __Hotfix0__IsCameraLoading; // 0x30
	private static DelegateBridge __Hotfix0__SetUpPageCtrlImpl; // 0x38
	private static DelegateBridge __Hotfix0__OnOpenUIPage; // 0x40
	private static DelegateBridge __Hotfix0__OpenPage; // 0x48
	private static DelegateBridge __Hotfix0__OnBattleCtrlDispose; // 0x50
	private static DelegateBridge __Hotfix0_Dispose; // 0x58


	// RVA: 0x1bdc82c VA: 0x75941f482c
	private Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Boolean ShowCustomDialog(DynDialogParam dialogParam, OptionType options) { }
	// RVA: 0x1bdcb48 VA: 0x75941f4b48
	public Void _OpenActivityPage(Object arg) { }
	// RVA: 0x1bdccc0 VA: 0x75941f4cc0
	private Void _OnInitCallback(Object obj) { }
	// RVA: 0x1bdca48 VA: 0x75941f4a48
	private Void _SetupPageCtrlIfExist() { }
	// RVA: 0x1bdd380 VA: 0x75941f5380
	private IEnumerator _SetUpWhenUICameraControllerReady() { }
	// RVA: 0x1bdcd3c VA: 0x75941f4d3c
	private Boolean _IsCameraLoading() { }
	// RVA: 0x1bdcf00 VA: 0x75941f4f00
	private Void _SetUpPageCtrlImpl() { }
	// RVA: 0x1bdd5ac VA: 0x75941f55ac
	private Void _OnOpenUIPage(Object obj) { }
	// RVA: 0x1bdd6a4 VA: 0x75941f56a4
	private Void _OpenPage(String key, UIPageOption param) { }
	// RVA: 0x1bdd7bc VA: 0x75941f57bc
	private Void _OnBattleCtrlDispose(Object arg) { }
	// RVA: 0x1bdd978 VA: 0x75941f5978
	public Void Dispose() { }
}
```