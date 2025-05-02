# Act3D0GachaBoxItem

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Image _boxImage`

- `GameObject _lockedObj`

- `GameObject _outOfStack`

- `Animator _animator`

- `Image _shadow`

- `Int32 m_cacheId`


## Methods

- `Void Render(Int32, Act3D0GachaBoxInfo)`

- `Void OnFocus(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0GachaBoxItem : MonoBehaviour, IHotfixable
{
	private Image _boxImage; // 0x18
	private GameObject _lockedObj; // 0x20
	private GameObject _outOfStack; // 0x28
	private Animator _animator; // 0x30
	private Image _shadow; // 0x38
	private Int32 m_cacheId; // 0x40
	private const String ANIM_PARAM; // 0x0
	private const String START_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnFocus; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32330dc VA: 0x759584b0dc
	public Void Render(Int32 id, Act3D0GachaBoxInfo info) { }
	// RVA: 0x32333e4 VA: 0x759584b3e4
	public Void OnFocus(Int32 orderId) { }
	// RVA: 0x32334b4 VA: 0x759584b4b4
	public Void .ctor() { }
}
```