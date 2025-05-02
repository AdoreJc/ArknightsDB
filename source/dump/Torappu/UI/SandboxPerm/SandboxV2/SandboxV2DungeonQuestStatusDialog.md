# SandboxV2DungeonQuestStatusDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasObject _iconAtalsObject`

- `SandboxV2DungeonQuestBannerView _completedView`

- `SandboxV2DungeonQuestBannerView _startView`

- `SandboxV2DungeonQuestBannerView _faieldView`


## Methods

- `Param _CreateBannerViewParam()`

- `Void _OnBannerQuit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonQuestStatusDialog : UICompDialog`1
{
	private List`1 _questLineIcons; // 0x48
	private UIAtlasObject _iconAtalsObject; // 0x50
	private SandboxV2DungeonQuestBannerView _completedView; // 0x58
	private SandboxV2DungeonQuestBannerView _startView; // 0x60
	private SandboxV2DungeonQuestBannerView _faieldView; // 0x68
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__CreateBannerViewParam; // 0x8
	private static DelegateBridge __Hotfix0__OnBannerQuit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x252daf8 VA: 0x7594b45af8
	protected override Void OnRender(Option input) { }
	// RVA: 0x252dd6c VA: 0x7594b45d6c
	private Param _CreateBannerViewParam() { }
	// RVA: 0x252df3c VA: 0x7594b45f3c
	private Void _OnBannerQuit() { }
	// RVA: 0x252e010 VA: 0x7594b46010
	public Void .ctor() { }
}
```