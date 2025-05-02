# ShopDetailProgressGPView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _textProgress`

- `GameObject _panelRemain`

- `Text _textRemainCount`

- `SimpleLayoutContent _contentReward`

- `ScrollRect _scrollRect`

- `Image _spriteImage`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel, SpriteHub)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailProgressGPView : ShopDetailCommonView, IHotfixable
{
	private const String CHECK_IN_PROGRESS_FORMAT; // 0x0
	private Text _textProgress; // 0xa8
	private GameObject _panelRemain; // 0xb0
	private Text _textRemainCount; // 0xb8
	private SimpleLayoutContent _contentReward; // 0xc0
	private ScrollRect _scrollRect; // 0xc8
	private Image _spriteImage; // 0xd0
	private Boolean m_hasInited; // 0xd8
	private List`1 m_cachedModelList; // 0xe0
	private Adapter m_adapter; // 0xe8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x243af00 VA: 0x7594a52f00
	public override Void ApplyData(DetailCommonViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x243b1e0 VA: 0x7594a531e0
	private Void _InitIfNot() { }
	// RVA: 0x243b344 VA: 0x7594a53344
	public Void .ctor() { }
	// RVA: 0x243b3b4 VA: 0x7594a533b4
	private Void <>xLuaBaseProxy_ApplyData(DetailCommonViewModel P0, SpriteHub P1) { }
}
```