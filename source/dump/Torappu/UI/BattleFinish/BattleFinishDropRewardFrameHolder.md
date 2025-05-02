# BattleFinishDropRewardFrameHolder

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `RectTransform _frameViewRoot`

- `LayoutGroup _rewardLayout`

- `BattleFinishDropRewardFrameView m_frameView`


## Methods

- `Void _ClearFrameView()`

- `Void RenderFrameView(BattleStageInfo, DropInfoGroupViewModel, UIAssetLoader)`

- `Void _ResetRewardLayout()`

- `Boolean _TryLoadFrameView(String, UIAssetLoader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishDropRewardFrameHolder : MonoBehaviour, IHotfixable
{
	private const Int32 DEFAULT_LAYOUT_PADDING_LEFT; // 0x0
	private const Int32 DEFAULT_LAYOUT_PADDING_RIGHT; // 0x0
	private RectTransform _frameViewRoot; // 0x18
	private LayoutGroup _rewardLayout; // 0x20
	private BattleFinishDropRewardFrameView m_frameView; // 0x28
	private static DelegateBridge __Hotfix0__ClearFrameView; // 0x0
	private static DelegateBridge __Hotfix0_RenderFrameView; // 0x8
	private static DelegateBridge __Hotfix0__ResetRewardLayout; // 0x10
	private static DelegateBridge __Hotfix0__TryLoadFrameView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2e93e68 VA: 0x75954abe68
	private Void _ClearFrameView() { }
	// RVA: 0x2e91804 VA: 0x75954a9804
	public Void RenderFrameView(BattleStageInfo stageInfo, DropInfoGroupViewModel dropInfoGroupViewModel, UIAssetLoader assetLoader) { }
	// RVA: 0x2e940c8 VA: 0x75954ac0c8
	private Void _ResetRewardLayout() { }
	// RVA: 0x2e93f74 VA: 0x75954abf74
	private Boolean _TryLoadFrameView(String panelPath, UIAssetLoader assetLoader) { }
	// RVA: 0x2e94164 VA: 0x75954ac164
	public Void .ctor() { }
}
```