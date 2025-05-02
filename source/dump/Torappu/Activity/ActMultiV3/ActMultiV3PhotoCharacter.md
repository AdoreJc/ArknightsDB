# ActMultiV3PhotoCharacter

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UISpineHolder _spineHolder`

- `UIAtlasImage _shadowImage`

- `Boolean m_inited`

- `UIBuildingSpineAdapter m_spineImpl`


## Methods

- `Void Render(ActMultiV3PhotoCharViewModel, UIColorGraphic)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoCharacter : MonoBehaviour, IHotfixable
{
	private UISpineHolder _spineHolder; // 0x18
	private UIAtlasImage _shadowImage; // 0x20
	private Boolean m_inited; // 0x28
	private UIBuildingSpineAdapter m_spineImpl; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x311b148 VA: 0x7595733148
	public Void Render(ActMultiV3PhotoCharViewModel charModel, UIColorGraphic characterGraphic) { }
	// RVA: 0x311b430 VA: 0x7595733430
	private Void _InitIfNot() { }
	// RVA: 0x311b4c4 VA: 0x75957334c4
	public Void .ctor() { }
}
```