# SandboxV2ChallengeRewardDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIRenderTextureImage _blurBackground`

- `RectTransform _backRect`

- `GameObject _pnlReceiveAll`

- `SimpleLayoutContent _rewardContainer`

- `SandboxV2ChallengeRewardGroupViewModel m_viewModel`

- `Adapter m_adapter`

- `Boolean m_inited`

- `String m_cachedTopicId`


## Methods

- `Void _InitIfNot()`

- `Void _Render()`

- `Void _Refresh()`

- `Void OnBackEvent()`

- `Void _SendReceiveRewardRequest(List`1)`

- `Void _OnReceiveRequestResponded(SandboxV2GetChallengeRewardResponse)`

- `Void _OnReceiveBtnClicked(String)`

- `Void OnReceiveAllBtnClicked()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeRewardDialog : UICompDialog`1
{
	private UIRenderTextureImage _blurBackground; // 0x48
	private RectTransform _backRect; // 0x50
	private GameObject _pnlReceiveAll; // 0x58
	private SimpleLayoutContent _rewardContainer; // 0x60
	private SandboxV2ChallengeRewardGroupViewModel m_viewModel; // 0x68
	private Adapter m_adapter; // 0x70
	private Boolean m_inited; // 0x78
	private String m_cachedTopicId; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__Refresh; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x20
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x28
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x30
	private static DelegateBridge __Hotfix0__SendReceiveRewardRequest; // 0x38
	private static DelegateBridge __Hotfix0__OnReceiveRequestResponded; // 0x40
	private static DelegateBridge __Hotfix0__OnReceiveBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnReceiveAllBtnClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x25ca53c VA: 0x7594be253c
	private Void _InitIfNot() { }
	// RVA: 0x25ca6a0 VA: 0x7594be26a0
	private Void _Render() { }
	// RVA: 0x25ca738 VA: 0x7594be2738
	private Void _Refresh() { }
	// RVA: 0x25cac5c VA: 0x7594be2c5c
	protected override Void OnInit() { }
	// RVA: 0x25cad6c VA: 0x7594be2d6c
	protected override Void OnRender(Options input) { }
	// RVA: 0x25cae0c VA: 0x7594be2e0c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x25cae74 VA: 0x7594be2e74
	public Void OnBackEvent() { }
	// RVA: 0x25caf40 VA: 0x7594be2f40
	private Void _SendReceiveRewardRequest(List`1 rewardIds) { }
	// RVA: 0x25cb148 VA: 0x7594be3148
	private Void _OnReceiveRequestResponded(SandboxV2GetChallengeRewardResponse response) { }
	// RVA: 0x25cb298 VA: 0x7594be3298
	private Void _OnReceiveBtnClicked(String rewardId) { }
	// RVA: 0x25cb41c VA: 0x7594be341c
	public Void OnReceiveAllBtnClicked() { }
	// RVA: 0x25cb5f8 VA: 0x7594be35f8
	public Void .ctor() { }
	// RVA: 0x25cb788 VA: 0x7594be3788
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x25cb790 VA: 0x7594be3790
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```