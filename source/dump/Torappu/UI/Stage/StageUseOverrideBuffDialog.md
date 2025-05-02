# StageUseOverrideBuffDialog

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIRenderTextureImage _blurImg`

- `Transform _startContainer`

- `StageStartBattleETButton _etButton`

- `SimpleLayoutContent _rewardContent`

- `Text _name`

- `Text _enName`

- `Text _ensureText`

- `Text _descText`

- `Text _remainCount`

- `Image _iconImg`

- `Image _countImg`

- `Single _scaler`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `StageStartBattleETButton m_etButton`

- `Action m_onClickAction`


## Methods

- `Void _InitIfNot()`

- `Void OnClick()`

- `Void OnClose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageUseOverrideBuffDialog : UICustomDialog`1
{
	private UIRenderTextureImage _blurImg; // 0x50
	private Transform _startContainer; // 0x58
	private StageStartBattleETButton _etButton; // 0x60
	private SimpleLayoutContent _rewardContent; // 0x68
	private Text _name; // 0x70
	private Text _enName; // 0x78
	private Text _ensureText; // 0x80
	private Text _descText; // 0x88
	private Text _remainCount; // 0x90
	private Image _iconImg; // 0x98
	private Image _countImg; // 0xa0
	private Single _scaler; // 0xa8
	private Adapter m_adapter; // 0xb0
	private Boolean m_isInited; // 0xb8
	private StageStartBattleETButton m_etButton; // 0xc0
	private Action m_onClickAction; // 0xc8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnClose; // 0x10
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2f9bd38 VA: 0x75955b3d38
	private Void _InitIfNot() { }
	// RVA: 0x2f9bf88 VA: 0x75955b3f88
	public Void OnClick() { }
	// RVA: 0x2f9c01c VA: 0x75955b401c
	public Void OnClose() { }
	// RVA: 0x2f9c0a0 VA: 0x75955b40a0
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2f9c108 VA: 0x75955b4108
	protected override Void OnRender(Option options) { }
	// RVA: 0x2f9c5b0 VA: 0x75955b45b0
	public Void .ctor() { }
}
```