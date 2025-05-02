# CrossAppShareController

**Namespace:** `Torappu.UI.CrossAppShare`


## Fields

- `InputOption m_cachedInputOption`

- `Coroutine m_shotCoroutine`

- `IEnumerator m_shotTween`

- `Tween m_flashInTween`

- `Tween m_flashOutTween`

- `Tween m_displayEffectTween`

- `CrossAppShareRemakeController m_remakeController`

- `Boolean m_isAvail`

- `CrossAppShareErrorCode m_errorCode`

- `Boolean <isShotting>k__BackingField`

- `Boolean <isWorking>k__BackingField`


## Properties

- `Boolean isShotting`

- `Boolean isAvail`

- `Boolean isWorking`

- `CrossAppShareErrorCode errorCode`


## Methods

- `Void _InitMessageCallBack()`

- `Void _DisposeMessageCallBack()`

- `Void OnInit()`

- `Void Dispose()`

- `IEnumerator GetShotTween()`

- `Boolean get_isShotting()`

- `Void set_isShotting(Boolean)`

- `Boolean get_isAvail()`

- `Boolean get_isWorking()`

- `Void set_isWorking(Boolean)`

- `CrossAppShareErrorCode get_errorCode()`

- `IEnumerator _ShotAction()`

- `Void _OnShareCallBackHandler(ShareCallBackMessage)`

- `Void _InstantiateRemakeController()`

- `Void _AdjustRenderCanvasAndCamera(Vector2)`

- `Void _DoRemake(ICrossAppShareModelCollector, ILoadAsset, ICrossAppShareRemakeAdditionBaseModel)`

- `IEnumerator _DoShot(Vector2)`

- `Void _DisplayShot(Vector2)`

- `String _GetShotImgPath()`

- `Void <_InitMessageCallBack>b__15_0(ShareCallBackMessage)`

- `Void <_OnShareCallBackHandler>b__33_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrossAppShare
public class CrossAppShareController : IHotfixable, IDisposable
{
	private const Single MAX_SHARE_SIZE_MB; // 0x0
	private static CrossAppShareController m_controller; // 0x0
	private const String IMG_PATH; // 0x0
	private InputOption m_cachedInputOption; // 0x10
	private Coroutine m_shotCoroutine; // 0x78
	private IEnumerator m_shotTween; // 0x80
	private Tween m_flashInTween; // 0x88
	private Tween m_flashOutTween; // 0x90
	private Tween m_displayEffectTween; // 0x98
	private CrossAppShareRemakeController m_remakeController; // 0xa0
	private Boolean m_isAvail; // 0xa8
	private CrossAppShareErrorCode m_errorCode; // 0xac
	private Boolean <isShotting>k__BackingField; // 0xb0
	private Boolean <isWorking>k__BackingField; // 0xb1
	private static DelegateBridge __Hotfix0_TryRegisterController; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0__InitMessageCallBack; // 0x18
	private static DelegateBridge __Hotfix0__DisposeMessageCallBack; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_Dispose; // 0x30
	private static DelegateBridge __Hotfix0_GetShotTween; // 0x38
	private static DelegateBridge __Hotfix0_get_isShotting; // 0x40
	private static DelegateBridge __Hotfix0_set_isShotting; // 0x48
	private static DelegateBridge __Hotfix0_get_isAvail; // 0x50
	private static DelegateBridge __Hotfix0_get_isWorking; // 0x58
	private static DelegateBridge __Hotfix0_set_isWorking; // 0x60
	private static DelegateBridge __Hotfix0_get_errorCode; // 0x68
	private static DelegateBridge __Hotfix0__ShotAction; // 0x70
	private static DelegateBridge __Hotfix0__OnShareCallBackHandler; // 0x78
	private static DelegateBridge __Hotfix0__InstantiateRemakeController; // 0x80
	private static DelegateBridge __Hotfix0__AdjustRenderCanvasAndCamera; // 0x88
	private static DelegateBridge __Hotfix0__DoRemake; // 0x90
	private static DelegateBridge __Hotfix0__DoShot; // 0x98
	private static DelegateBridge __Hotfix0__DisplayShot; // 0xa0
	private static DelegateBridge __Hotfix0__GetShotImgPath; // 0xa8

	public Boolean isShotting { get; set; }
	public Boolean isAvail { get; }
	public Boolean isWorking { get; set; }
	public CrossAppShareErrorCode errorCode { get; }

	// RVA: 0x2bbd414 VA: 0x75951d5414
	public static CrossAppShareController TryRegisterController(InputOption inputOption) { }
	// RVA: 0x2bbd5a0 VA: 0x75951d55a0
	private Void .ctor() { }
	// RVA: 0x2bbd6b0 VA: 0x75951d56b0
	private Void _InitMessageCallBack() { }
	// RVA: 0x2bbd794 VA: 0x75951d5794
	private Void _DisposeMessageCallBack() { }
	// RVA: 0x2bbd610 VA: 0x75951d5610
	public Void OnInit() { }
	// RVA: 0x2bbd920 VA: 0x75951d5920
	public Void Dispose() { }
	// RVA: 0x2bbda80 VA: 0x75951d5a80
	public IEnumerator GetShotTween() { }
	// RVA: 0x2bbdbb8 VA: 0x75951d5bb8
	public Boolean get_isShotting() { }
	// RVA: 0x2bbd820 VA: 0x75951d5820
	private Void set_isShotting(Boolean value) { }
	// RVA: 0x2bbdc20 VA: 0x75951d5c20
	public Boolean get_isAvail() { }
	// RVA: 0x2bbdc88 VA: 0x75951d5c88
	public Boolean get_isWorking() { }
	// RVA: 0x2bbd8a0 VA: 0x75951d58a0
	private Void set_isWorking(Boolean value) { }
	// RVA: 0x2bbdcf0 VA: 0x75951d5cf0
	public CrossAppShareErrorCode get_errorCode() { }
	// RVA: 0x2bbdb0c VA: 0x75951d5b0c
	private IEnumerator _ShotAction() { }
	// RVA: 0x2bbdd80 VA: 0x75951d5d80
	private Void _OnShareCallBackHandler(ShareCallBackMessage message) { }
	// RVA: 0x2bbdf6c VA: 0x75951d5f6c
	private Void _InstantiateRemakeController() { }
	// RVA: 0x2bbe0e4 VA: 0x75951d60e4
	private Void _AdjustRenderCanvasAndCamera(Vector2 sizeDelta) { }
	// RVA: 0x2bbe1b4 VA: 0x75951d61b4
	private Void _DoRemake(ICrossAppShareModelCollector modelCollector, ILoadAsset iLoadAsset, ICrossAppShareRemakeAdditionBaseModel additionModel) { }
	// RVA: 0x2bbe380 VA: 0x75951d6380
	private IEnumerator _DoShot(Vector2 shotRTResolution) { }
	// RVA: 0x2bbe474 VA: 0x75951d6474
	private Void _DisplayShot(Vector2 shotCanvasSize) { }
	// RVA: 0x2bbe7e8 VA: 0x75951d67e8
	private String _GetShotImgPath() { }
	// RVA: 0x2bbe86c VA: 0x75951d686c
	private Void <_InitMessageCallBack>b__15_0(ShareCallBackMessage val) { }
	// RVA: 0x2bbe870 VA: 0x75951d6870
	private Void <_OnShareCallBackHandler>b__33_0() { }
}
```