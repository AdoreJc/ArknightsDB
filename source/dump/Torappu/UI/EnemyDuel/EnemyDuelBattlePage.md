# EnemyDuelBattlePage

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelBattlePageVirtualCameraCanvasBinder _canvasBinder`

- `RectTransform _dialogContainer`

- `CanvasGroup _connectDlg`

- `UIPageVirtualCamera m_virtualCamera`

- `UIPageVirtualCamera m_blurCamera`

- `BlurCamBinder m_blurCamBinder`

- `UICompDialogMgr m_dlgMgr`

- `FadeSwitchTween m_connectDlgTween`

- `Int32 m_giveUpDlg`

- `Boolean m_isAbnormalEnd`


## Properties

- `UICompDialogMgr dlgMgr`


## Methods

- `UICompDialogMgr get_dlgMgr()`

- `Void InitVirtualCamera(UIPageCameraProvider)`

- `Void DisposeVirtualCamera()`

- `Void LoadAllVirtualCamTypes(ICollection`1)`

- `Void ShotBlurRT(UIRenderTextureImage)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _GetBlurCameras(IList`1)`

- `Void _RegisterBattleEvents()`

- `Void _OpenRoomEndDialog(Object)`

- `Void _OnNetStateChanged(Object)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattlePage : StateEnginePage, IVirtualCameraPage, IValueMsgReceiver, ICompDialogCallBack
{
	public const Int32 MSG_GIVE_UP_BTN_CLICKED; // 0x0
	public const Int32 MSG_GIVE_UP; // 0x0
	private EnemyDuelBattlePageVirtualCameraCanvasBinder _canvasBinder; // 0xe8
	private RectTransform _dialogContainer; // 0xf0
	private CanvasGroup _connectDlg; // 0xf8
	private UIPageVirtualCamera m_virtualCamera; // 0x100
	private UIPageVirtualCamera m_blurCamera; // 0x108
	private SetWhenBind`2 m_cameraSetter; // 0x110
	private BlurCamBinder m_blurCamBinder; // 0x118
	private UICompDialogMgr m_dlgMgr; // 0x120
	private FadeSwitchTween m_connectDlgTween; // 0x128
	private Int32 m_giveUpDlg; // 0x130
	private Boolean m_isAbnormalEnd; // 0x134
	private static DelegateBridge __Hotfix0_get_dlgMgr; // 0x0
	private static DelegateBridge __Hotfix0_InitVirtualCamera; // 0x8
	private static DelegateBridge __Hotfix0_DisposeVirtualCamera; // 0x10
	private static DelegateBridge __Hotfix0_LoadAllVirtualCamTypes; // 0x18
	private static DelegateBridge __Hotfix0_ShotBlurRT; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x38
	private static DelegateBridge __Hotfix0_OnStart; // 0x40
	private static DelegateBridge __Hotfix0__EnsureCameraSetter; // 0x48
	private static DelegateBridge __Hotfix0__GetBlurCameras; // 0x50
	private static DelegateBridge __Hotfix0__RegisterBattleEvents; // 0x58
	private static DelegateBridge __Hotfix0__OpenRoomEndDialog; // 0x60
	private static DelegateBridge __Hotfix0__OnNetStateChanged; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public UICompDialogMgr dlgMgr { get; }

	// RVA: 0x2987b64 VA: 0x7594f9fb64
	public UICompDialogMgr get_dlgMgr() { }
	// RVA: 0x29880d4 VA: 0x7594fa00d4
	public Void InitVirtualCamera(UIPageCameraProvider provider) { }
	// RVA: 0x29884a4 VA: 0x7594fa04a4
	public Void DisposeVirtualCamera() { }
	// RVA: 0x2988528 VA: 0x7594fa0528
	public Void LoadAllVirtualCamTypes(ICollection`1 cameraTypes) { }
	// RVA: 0x29886e0 VA: 0x7594fa06e0
	public Void ShotBlurRT(UIRenderTextureImage rtImage) { }
	// RVA: 0x29887c4 VA: 0x7594fa07c4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x29889a0 VA: 0x7594fa09a0
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2988a7c VA: 0x7594fa0a7c
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2988c44 VA: 0x7594fa0c44
	protected override Void OnStart() { }
	// RVA: 0x2988260 VA: 0x7594fa0260
	private SetWhenBind`2 _EnsureCameraSetter() { }
	// RVA: 0x2988e6c VA: 0x7594fa0e6c
	private Void _GetBlurCameras(IList`1 cameras) { }
	// RVA: 0x2988d00 VA: 0x7594fa0d00
	private Void _RegisterBattleEvents() { }
	// RVA: 0x29890ac VA: 0x7594fa10ac
	private Void _OpenRoomEndDialog(Object arg) { }
	// RVA: 0x29892e8 VA: 0x7594fa12e8
	private Void _OnNetStateChanged(Object arg) { }
	// RVA: 0x29893e8 VA: 0x7594fa13e8
	public Void .ctor() { }
	// RVA: 0x2989458 VA: 0x7594fa1458
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2989460 VA: 0x7594fa1460
	private Void <>xLuaBaseProxy_OnStart() { }
}
```