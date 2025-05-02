# ShopDetailProgressGPItemView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _textCheckInProgress`

- `SimpleLayoutContent _contentRewards`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Methods

- `Void Render(CheckInRewardModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailProgressGPItemView : MonoBehaviour, IHotfixable
{
	private Text _textCheckInProgress; // 0x18
	private SimpleLayoutContent _contentRewards; // 0x20
	private Boolean m_hasInited; // 0x28
	private List`1 m_cachedRewards; // 0x30
	private Adapter m_adapter; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x243a764 VA: 0x7594a52764
	public Void Render(CheckInRewardModel viewModel) { }
	// RVA: 0x243a8a8 VA: 0x7594a528a8
	private Void _InitIfNot() { }
	// RVA: 0x243aa0c VA: 0x7594a52a0c
	public Void .ctor() { }
}
```