# UIEffectHelper

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _psPrefab`

- `Boolean _playAtStart`

- `Graphic _playOnUIElem`

- `Single _lifeTime`

- `GameObject _effectInst`


## Properties

- `Single lifeTime`

- `Boolean isPlaying`


## Methods

- `Single get_lifeTime()`

- `Boolean get_isPlaying()`

- `Void Awake()`

- `Void Start()`

- `Void Play()`

- `Void Stop()`

- `Int32 _SortCompare(Renderer, Renderer)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIEffectHelper : MonoBehaviour, IHotfixable
{
	private GameObject _psPrefab; // 0x18
	private Boolean _playAtStart; // 0x20
	private Graphic _playOnUIElem; // 0x28
	private Single _lifeTime; // 0x30
	private const String ROOT_PS_PATH; // 0x0
	private GameObject _effectInst; // 0x38
	private static DelegateBridge __Hotfix0_get_lifeTime; // 0x0
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x8
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge __Hotfix0_Play; // 0x20
	private static DelegateBridge __Hotfix0_Stop; // 0x28
	private static DelegateBridge __Hotfix0__SortCompare; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Single lifeTime { get; }
	public Boolean isPlaying { get; }

	// RVA: 0x22461f0 VA: 0x759485e1f0
	public Single get_lifeTime() { }
	// RVA: 0x2246258 VA: 0x759485e258
	public Boolean get_isPlaying() { }
	// RVA: 0x22462f0 VA: 0x759485e2f0
	private Void Awake() { }
	// RVA: 0x2246480 VA: 0x759485e480
	private Void Start() { }
	// RVA: 0x22464fc VA: 0x759485e4fc
	public Void Play() { }
	// RVA: 0x2246770 VA: 0x759485e770
	public Void Stop() { }
	// RVA: 0x2246854 VA: 0x759485e854
	private Int32 _SortCompare(Renderer r1, Renderer r2) { }
	// RVA: 0x2246900 VA: 0x759485e900
	public Void .ctor() { }
}
```