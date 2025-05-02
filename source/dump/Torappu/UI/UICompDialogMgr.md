# UICompDialogMgr

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform m_container`

- `Canvas m_canvas`

- `Camera m_camera`

- `MgrHost m_host`

- `AutoUnloadAssets m_dialogLoader`


## Methods

- `Void CollectUsedAssets(ICollection`1)`

- `Boolean OpenDialog(UICompBuilder`2, out)`

- `Void CloseAllDialog()`

- `Void ClearAllDialog()`

- `Void DialogOnly_OnDialogConfirm(Int32, ValueBundle)`

- `Void DialogOnly_OnDialogClose(Int32)`

- `IEnumerator _HideSingleDialogCoroutine(DialogBase)`

- `IEnumerator _HideDialogCoroutine(DialogWrapper)`

- `IEnumerator _HideAllDialogCoroutine()`

- `Void GetViewAbleCameras(IList`1)`

- `Boolean CheckIfValidCallback(Transform)`

- `Dialog _CreateAndRegisterDialogInst(String, out)`

- `Void _ClearAllDialog()`

- `Void _ResumeAllDialog()`

- `Void _OnHostClosed()`

- `Void _OnHostResumed()`

- `Void _ManagedDestroyDialog(DialogBase)`

- `Void _BindDialogCallbackImpl(CallbackHandler, Int32)`

- `Void BindStateCallBack(CallBackHandler, Int32)`

- `Void BindPageComponentCallBack(CallBackHandler, Int32)`

- `Void BindDialogCallBack(CallBackHandler, Int32)`

- `Void BindAllCallBack(CallBackHandler)`

- `Void UnbindCallBack(CallBackHandler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICompDialogMgr : IHotfixable, IHost
{
	private ListDict`2 m_dialogDict; // 0x10
	private List`1 m_allCallBackList; // 0x18
	private RectTransform m_container; // 0x20
	private Canvas m_canvas; // 0x28
	private Camera m_camera; // 0x30
	private List`1 m_viewableCameras; // 0x38
	private MgrHost m_host; // 0x40
	private AutoUnloadAssets m_dialogLoader; // 0x48
	private static DelegateBridge __Hotfix0_Build; // 0x0
	private static DelegateBridge __Hotfix0__BuildImpl; // 0x8
	private static DelegateBridge __Hotfix0_CollectUsedAssets; // 0x10
	private static DelegateBridge __Hotfix0_OpenDialog; // 0x18
	private static DelegateBridge __Hotfix0_CloseAllDialog; // 0x20
	private static DelegateBridge __Hotfix0_ClearAllDialog; // 0x28
	private static DelegateBridge __Hotfix0_DialogOnly_OnDialogConfirm; // 0x30
	private static DelegateBridge __Hotfix0_DialogOnly_OnDialogClose; // 0x38
	private static DelegateBridge __Hotfix0__HideSingleDialogCoroutine; // 0x40
	private static DelegateBridge __Hotfix0__HideDialogCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__HideAllDialogCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_GetViewAbleCameras; // 0x58
	private static DelegateBridge __Hotfix0_CheckIfValidCallback; // 0x60
	private static DelegateBridge __Hotfix0__GetViewAbleCameras; // 0x68
	private static DelegateBridge __Hotfix0__CreateAndRegisterDialogInst; // 0x70
	private static DelegateBridge __Hotfix0__ClearAllDialog; // 0x78
	private static DelegateBridge __Hotfix0__ResumeAllDialog; // 0x80
	private static DelegateBridge __Hotfix0__OnHostClosed; // 0x88
	private static DelegateBridge __Hotfix0__OnHostResumed; // 0x90
	private static DelegateBridge __Hotfix0__ManagedDestroyDialog; // 0x98
	private static DelegateBridge __Hotfix0__BindDialogCallbackImpl; // 0xa0
	private static DelegateBridge __Hotfix0_BindStateCallBack; // 0xa8
	private static DelegateBridge __Hotfix0_BindPageComponentCallBack; // 0xb0
	private static DelegateBridge __Hotfix0_BindDialogCallBack; // 0xb8
	private static DelegateBridge __Hotfix0_BindAllCallBack; // 0xc0
	private static DelegateBridge __Hotfix0_UnbindCallBack; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0


	// RVA: 0x22635c0 VA: 0x759487b5c0
	public static UICompDialogMgr Build(MgrBuilder mgrBuilder, UIPage page) { }
	// RVA: 0x22637d4 VA: 0x759487b7d4
	private static UICompDialogMgr _BuildImpl(MgrBuilder mgrBuilder, MgrHost host) { }
	// RVA: 0x2263ebc VA: 0x759487bebc
	public Void CollectUsedAssets(ICollection`1 usedAssets) { }
	// RVA: 0x VA: 0x0
	public Boolean OpenDialog(UICompBuilder`2 builder, out Int32 instId) { }
	// RVA: 0x2264110 VA: 0x759487c110
	public Void CloseAllDialog() { }
	// RVA: 0x2264244 VA: 0x759487c244
	public Void ClearAllDialog() { }
	// RVA: 0x2264484 VA: 0x759487c484
	public Void DialogOnly_OnDialogConfirm(Int32 instId, ValueBundle value) { }
	// RVA: 0x226476c VA: 0x759487c76c
	public Void DialogOnly_OnDialogClose(Int32 instId) { }
	// RVA: 0x2264934 VA: 0x759487c934
	private IEnumerator _HideSingleDialogCoroutine(DialogBase dialog) { }
	// RVA: 0x2264864 VA: 0x759487c864
	private IEnumerator _HideDialogCoroutine(DialogWrapper wrapper) { }
	// RVA: 0x2264198 VA: 0x759487c198
	private IEnumerator _HideAllDialogCoroutine() { }
	// RVA: 0x2264a7c VA: 0x759487ca7c
	public Void GetViewAbleCameras(IList`1 cameras) { }
	// RVA: 0x2264c48 VA: 0x759487cc48
	public Boolean CheckIfValidCallback(Transform transform) { }
	// RVA: 0x2263bb8 VA: 0x759487bbb8
	private List`1 _GetViewAbleCameras(IList`1 cameras, Camera rootCamera) { }
	// RVA: 0x VA: 0x0
	private Dialog _CreateAndRegisterDialogInst(String resPath, out Boolean isExistingInst) { }
	// RVA: 0x22642ac VA: 0x759487c2ac
	private Void _ClearAllDialog() { }
	// RVA: 0x2264dd4 VA: 0x759487cdd4
	private Void _ResumeAllDialog() { }
	// RVA: 0x2265030 VA: 0x759487d030
	private Void _OnHostClosed() { }
	// RVA: 0x2265098 VA: 0x759487d098
	private Void _OnHostResumed() { }
	// RVA: 0x2264ce4 VA: 0x759487cce4
	private Void _ManagedDestroyDialog(DialogBase dialog) { }
	// RVA: 0x VA: 0x0
	private Void _BindDialogCallbackImpl(CallbackHandler handler, Int32 instId) { }
	// RVA: 0x VA: 0x0
	public Void BindStateCallBack(CallBackHandler handler, Int32 instId) { }
	// RVA: 0x VA: 0x0
	public Void BindPageComponentCallBack(CallBackHandler handler, Int32 instId) { }
	// RVA: 0x VA: 0x0
	public Void BindDialogCallBack(CallBackHandler handler, Int32 instId) { }
	// RVA: 0x VA: 0x0
	public Void BindAllCallBack(CallBackHandler handler) { }
	// RVA: 0x VA: 0x0
	public Void UnbindCallBack(CallBackHandler handler) { }
	// RVA: 0x2263aa4 VA: 0x759487baa4
	public Void .ctor() { }
}
```