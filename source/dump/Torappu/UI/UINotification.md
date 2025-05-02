# UINotification

**Namespace:** `Torappu.UI`


## Fields

- `VerticalLayoutGroup _notifySlideLayout`

- `RectTransform _notifyFloatLayout`

- `UINotifyViewHolder _viewHolder`

- `HostImpl m_hostImpl`


## Properties

- `Int32 assetGroupId`


## Methods

- `Int32 get_assetGroupId()`

- `Void FixedUpdate()`

- `T NotifyViewOnlyLoadAsset(String)`

- `Boolean AddRawNotifyView(NotifyViewOptions`2)`

- `Boolean _AddNotifyView(NotifyViewOptions`2)`

- `Void _TextToast(String, Single, Boolean)`

- `IEnumerator _ToastsCoroutine(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UINotification : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private const Single TOAST_BY_RESP_INTERVAL; // 0x0
	private VerticalLayoutGroup _notifySlideLayout; // 0x18
	private RectTransform _notifyFloatLayout; // 0x20
	private UINotifyViewHolder _viewHolder; // 0x28
	private HostImpl m_hostImpl; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_get_assetGroupId; // 0x8
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x10
	private static DelegateBridge __Hotfix0_NotifyViewOnlyLoadAsset; // 0x18
	private static DelegateBridge __Hotfix0_AddToast; // 0x20
	private static DelegateBridge __Hotfix0_AddRawNotifyView; // 0x28
	private static DelegateBridge __Hotfix0_TextToast; // 0x30
	private static DelegateBridge __Hotfix1_TextToast; // 0x38
	private static DelegateBridge __Hotfix0_FuncToast; // 0x40
	private static DelegateBridge __Hotfix0_DynFuncToast; // 0x48
	private static DelegateBridge __Hotfix0_LockToast; // 0x50
	private static DelegateBridge __Hotfix0_UnlockToast; // 0x58
	private static DelegateBridge __Hotfix0_MedalToast; // 0x60
	private static DelegateBridge __Hotfix0_ToastByResponse; // 0x68
	private static DelegateBridge __Hotfix0_Toasts; // 0x70
	private static DelegateBridge __Hotfix0__AddNotifyView; // 0x78
	private static DelegateBridge __Hotfix0__TextToast; // 0x80
	private static DelegateBridge __Hotfix0__BlockTextToast; // 0x88
	private static DelegateBridge __Hotfix0__ToastsCoroutine; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	protected Int32 assetGroupId { get; }

	// RVA: 0x22741bc VA: 0x759488c1bc
	protected override Void OnInit() { }
	// RVA: 0x22743a8 VA: 0x759488c3a8
	protected Int32 get_assetGroupId() { }
	// RVA: 0x2274414 VA: 0x759488c414
	private Void FixedUpdate() { }
	// RVA: 0x VA: 0x0
	public T NotifyViewOnlyLoadAsset(String path) { }
	// RVA: 0x VA: 0x0
	public static Boolean AddToast(NotifyViewOptions`2 options) { }
	// RVA: 0x VA: 0x0
	public Boolean AddRawNotifyView(NotifyViewOptions`2 options) { }
	// RVA: 0x2262ca8 VA: 0x759487aca8
	public static Void TextToast(String content, Single delay, Boolean useDeduplicate) { }
	// RVA: 0x226dc4c VA: 0x7594885c4c
	public static Void TextToast(String content, Boolean useDeduplicate) { }
	// RVA: 0x VA: 0x0
	public static Void FuncToast(ViewType prefab, ParamType param, Single delay) { }
	// RVA: 0x VA: 0x0
	public static Void DynFuncToast(String path, ParamType param, Single delay) { }
	// RVA: 0x2274780 VA: 0x759488c780
	public static Void LockToast(String text, Single delay) { }
	// RVA: 0x2274944 VA: 0x759488c944
	public static Void UnlockToast(String text, Single delay) { }
	// RVA: 0x2273870 VA: 0x759488b870
	public static Void MedalToast(List`1 medalList, Single delay, Single duration) { }
	// RVA: 0x2274af8 VA: 0x759488caf8
	public static Void ToastByResponse(IAlertResponse response) { }
	// RVA: 0x2274e68 VA: 0x759488ce68
	public static Void Toasts(List`1 toasts) { }
	// RVA: 0x VA: 0x0
	private Boolean _AddNotifyView(NotifyViewOptions`2 options) { }
	// RVA: 0x2274600 VA: 0x759488c600
	private Void _TextToast(String content, Single delay, Boolean useDeduplicate) { }
	// RVA: 0x2274f78 VA: 0x759488cf78
	private static String _BlockTextToast(String content) { }
	// RVA: 0x2274d98 VA: 0x759488cd98
	private IEnumerator _ToastsCoroutine(List`1 alerts) { }
	// RVA: 0x2275008 VA: 0x759488d008
	public Void .ctor() { }
}
```