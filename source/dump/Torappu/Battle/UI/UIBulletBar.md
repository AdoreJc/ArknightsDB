# UIBulletBar

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIImageOnPopulateMesh _image`

- `Single _gapFactor`

- `Color m_color`

- `Int32 m_useSmoothCnt`


## Methods

- `Void Awake()`

- `Void ShowBulletCount(Single, Single)`

- `Void <Awake>b__7_0(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBulletBar : MonoBehaviour, IHotfixable
{
	private UIImageOnPopulateMesh _image; // 0x18
	private Single _gapFactor; // 0x20
	private const Single PER_GAP_COUNT; // 0x0
	private const Int32 USE_SMOOTH_COUNT; // 0x0
	private const Int32 IGNORE_GAP_COUNT; // 0x0
	private Color m_color; // 0x24
	private Int32 m_useSmoothCnt; // 0x34
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_ShowBulletCount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x207bef0 VA: 0x7594693ef0
	private Void Awake() { }
	// RVA: 0x207c0a8 VA: 0x75946940a8
	public Void ShowBulletCount(Single maxCount, Single curCount) { }
	// RVA: 0x207c200 VA: 0x7594694200
	public Void .ctor() { }
	// RVA: 0x207c270 VA: 0x7594694270
	private Void <Awake>b__7_0(VertexHelper vertexHelper) { }
}
```