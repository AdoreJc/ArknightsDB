# Act24sideStagePreviewPlugin

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Color _rewardDetailBgTint`


## Methods

- `Sprite <>xLuaBaseProxy_LoadMapPreview(String, String, ILoadAsset)`

- `Boolean <>xLuaBaseProxy_TryGetRewardDetailBgTint(String, String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideStagePreviewPlugin : StagePreviewActPlugin
{
	private Color _rewardDetailBgTint; // 0x30
	private static DelegateBridge __Hotfix0_LoadMapPreview; // 0x0
	private static DelegateBridge __Hotfix0_TryGetRewardDetailBgTint; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32e2520 VA: 0x75958fa520
	public override Sprite LoadMapPreview(String actId, String stageId, ILoadAsset assetLoader) { }
	// RVA: 0x32e2874 VA: 0x75958fa874
	public override Boolean TryGetRewardDetailBgTint(String actId, String stageId, out Color bgTint) { }
	// RVA: 0x32e2914 VA: 0x75958fa914
	public Void .ctor() { }
	// RVA: 0x32e2984 VA: 0x75958fa984
	private Sprite <>xLuaBaseProxy_LoadMapPreview(String P0, String P1, ILoadAsset P2) { }
	// RVA: 0x32e298c VA: 0x75958fa98c
	private Boolean <>xLuaBaseProxy_TryGetRewardDetailBgTint(String P0, String P1, out Color P2) { }
}
```