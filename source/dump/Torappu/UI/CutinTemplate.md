# CutinTemplate

**Namespace:** `Torappu.UI`


## Fields

- `UIStencilGraphic _imgMask`

- `Single _scaleX`

- `Single _scaleY`

- `Single _duration`

- `GameObject _decoPrefab`

- `GameObject _emptyImg`

- `Transform _scaleTrans`

- `Sequence m_cutinSeq`

- `CutinTemplateDecoView m_cachedDeco`

- `String m_cachedName`


## Methods

- `Void ShowCutinMask(StencilChannel, CutinParam, Action, Transform)`

- `Void UpdateCutinMask(CutinParam)`

- `Void HideCutinMask(CutinParam, Action)`

- `Void _HideOncomplete(Action)`

- `Boolean _ShowEmptyImage(String)`

- `Boolean _CacheName(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CutinTemplate : MonoBehaviour, IHotfixable
{
	public UIStencilGraphic _imgMask; // 0x18
	public UIStencilComponent[] _components; // 0x20
	private Single _scaleX; // 0x28
	private Single _scaleY; // 0x2c
	private Single _duration; // 0x30
	private GameObject _decoPrefab; // 0x38
	private GameObject _emptyImg; // 0x40
	private Transform _scaleTrans; // 0x48
	private const Single DEFAULT_FADE_DURATION; // 0x0
	private const Single DEAFULT_ALPHA_ONE; // 0x0
	private const Single DEAFULT_ALPHA_ZERO; // 0x0
	private const String NAME_CHAR_EMPTY; // 0x0
	private Sequence m_cutinSeq; // 0x50
	private CutinTemplateDecoView m_cachedDeco; // 0x58
	private String m_cachedName; // 0x60
	private static DelegateBridge __Hotfix0_ShowCutinMask; // 0x0
	private static DelegateBridge __Hotfix0_UpdateCutinMask; // 0x8
	private static DelegateBridge __Hotfix0_HideCutinMask; // 0x10
	private static DelegateBridge __Hotfix0__HideOncomplete; // 0x18
	private static DelegateBridge __Hotfix0__ShowEmptyImage; // 0x20
	private static DelegateBridge __Hotfix0__CacheName; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x216e3a0 VA: 0x75947863a0
	public Void ShowCutinMask(StencilChannel channel, CutinParam cutinParam, Action cb, Transform decoContainer) { }
	// RVA: 0x216ecf4 VA: 0x7594786cf4
	public Void UpdateCutinMask(CutinParam cutinParam) { }
	// RVA: 0x216ef40 VA: 0x7594786f40
	public Void HideCutinMask(CutinParam cutinParam, Action cb) { }
	// RVA: 0x216f41c VA: 0x759478741c
	private Void _HideOncomplete(Action cb) { }
	// RVA: 0x216ec2c VA: 0x7594786c2c
	private Boolean _ShowEmptyImage(String charName) { }
	// RVA: 0x216ee78 VA: 0x7594786e78
	private Boolean _CacheName(String charName) { }
	// RVA: 0x216f528 VA: 0x7594787528
	public Void .ctor() { }
}
```