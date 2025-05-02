# EmoticonPagerPanelModel

**Namespace:** `Torappu.UI.Emoticon`


## Fields

- `Int32 pagerIndex`

- `Boolean isOnlyOneTheme`

- `Int32 maxThemeEmojiCnt`


## Properties

- `EmoticonThemeItemModel curEmoticonThemeModel`


## Methods

- `EmoticonThemeItemModel get_curEmoticonThemeModel()`

- `Void PagerMove(Int32)`

- `Void <>xLuaBaseProxy_ShowPanelLoadData(IEmoticonCustomConfig, ValueBundle, EmojiSceneType, GOPositionHolder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmoticonPagerPanelModel : EmoticonPanelBaseModel
{
	public Int32 pagerIndex; // 0x48
	public Boolean isOnlyOneTheme; // 0x4c
	public Int32 maxThemeEmojiCnt; // 0x50
	private static DelegateBridge __Hotfix0_get_curEmoticonThemeModel; // 0x0
	private static DelegateBridge __Hotfix0_ShowPanelLoadData; // 0x8
	private static DelegateBridge __Hotfix0_PagerMove; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public EmoticonThemeItemModel curEmoticonThemeModel { get; }

	// RVA: 0x29b7d84 VA: 0x7594fcfd84
	public EmoticonThemeItemModel get_curEmoticonThemeModel() { }
	// RVA: 0x29b7e24 VA: 0x7594fcfe24
	public override Void ShowPanelLoadData(IEmoticonCustomConfig customConfig, ValueBundle vb, EmojiSceneType chatSceneType, GOPositionHolder showPos) { }
	// RVA: 0x29b7978 VA: 0x7594fcf978
	public Void PagerMove(Int32 target) { }
	// RVA: 0x29b8030 VA: 0x7594fd0030
	public Void .ctor() { }
	// RVA: 0x29b809c VA: 0x7594fd009c
	private Void <>xLuaBaseProxy_ShowPanelLoadData(IEmoticonCustomConfig P0, ValueBundle P1, EmojiSceneType P2, GOPositionHolder P3) { }
}
```