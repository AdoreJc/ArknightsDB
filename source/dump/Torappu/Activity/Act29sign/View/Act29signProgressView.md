# Act29signProgressView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `Act29signExpandView _expandView`

- `Text _optionCompleteDescText`

- `Int32 m_dayIndex`

- `Model m_expandViewModel`


## Methods

- `Void Render(Act29signDynViewModel)`

- `Void _RenderExpandView(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signProgressView : MonoBehaviour, IHotfixable
{
	private const Single EXPAND_DELAY; // 0x0
	private Act29signExpandView _expandView; // 0x18
	private Text _optionCompleteDescText; // 0x20
	private Int32 m_dayIndex; // 0x28
	private Model m_expandViewModel; // 0x2c
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderExpandView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x325d8a0 VA: 0x75958758a0
	public Void Render(Act29signDynViewModel viewModel) { }
	// RVA: 0x325fd20 VA: 0x7595877d20
	private Void _RenderExpandView(Boolean isShow) { }
	// RVA: 0x325fddc VA: 0x7595877ddc
	public Void .ctor() { }
}
```