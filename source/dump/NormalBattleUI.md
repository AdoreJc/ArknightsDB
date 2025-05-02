# NormalBattleUI

**Namespace:** ` `


## Fields

- `GameObject _rootGo`

- `Text _textStageCode`

- `Text _textRatingDesc`

- `UIAtlasImage _imgRating`

- `GameObject _newRecordGo`

- `UIAtlasObject _atlas`

- `GameObject _noEffectPanelGo`

- `GameObject _effectPanelGo`

- `Act42D0BattleFinishEffectItemView _effectItemPrefab`

- `Boolean m_hasInited`


## Methods

- `Void Render(String, Act42D0FinishInfoModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class NormalBattleUI : IHotfixable
{
	private GameObject _rootGo; // 0x10
	private Text _textStageCode; // 0x18
	private Text _textRatingDesc; // 0x20
	private UIAtlasImage _imgRating; // 0x28
	private GameObject _newRecordGo; // 0x30
	private UIAtlasObject _atlas; // 0x38
	private GameObject _noEffectPanelGo; // 0x40
	private GameObject _effectPanelGo; // 0x48
	private RectTransform[] _effectContainerList; // 0x50
	private Act42D0BattleFinishEffectItemView _effectItemPrefab; // 0x58
	private const Int32 EFFECT_COL_COUNT; // 0x0
	private List`1 m_effectItemList; // 0x60
	private Boolean m_hasInited; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3205b8c VA: 0x759581db8c
	public Void Render(String actId, Act42D0FinishInfoModel finishInfoModel) { }
	// RVA: 0x3207148 VA: 0x759581f148
	private Void _InitIfNot() { }
	// RVA: 0x3207544 VA: 0x759581f544
	public Void .ctor() { }
}
```