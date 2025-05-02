# LayerAnimPlayer

**Namespace:** ` `


## Fields

- `SpineMixExtraLayer m_layer`


## Methods

- `Void ChangeAnim(String, Single, Boolean)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LayerAnimPlayer : MonoBehaviour, IHotfixable
{
	private Action`3 m_onAnimChange; // 0x18
	private ObjectPtr`1 m_owner; // 0x20
	private SpineMixExtraLayer m_layer; // 0x30
	private static DelegateBridge __Hotfix0_get_owner; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_ChangeAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected ObjectPtr`1 owner { get; }

	// RVA: 0x3f298f8 VA: 0x75965418f8
	protected ObjectPtr`1 get_owner() { }
	// RVA: 0x3f29880 VA: 0x7596541880
	public virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x3f29668 VA: 0x7596541668
	public virtual Void Init(SpineMixExtraLayer layer, ObjectPtr`1 owner) { }
	// RVA: 0x3f29d44 VA: 0x7596541d44
	protected Void ChangeAnim(String animKey, Single alpha, Boolean isLoop) { }
	// RVA: 0x3f2a70c VA: 0x759654270c
	private Void OnDestroy() { }
	// RVA: 0x3f29e6c VA: 0x7596541e6c
	public Void .ctor() { }
}
```