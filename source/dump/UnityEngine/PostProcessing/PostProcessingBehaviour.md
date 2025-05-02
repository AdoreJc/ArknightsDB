# PostProcessingBehaviour

**Namespace:** `UnityEngine.PostProcessing`


## Fields

- `PostProcessingProfile profile`

- `MaterialFactory m_MaterialFactory`

- `RenderTextureFactory m_RenderTextureFactory`

- `PostProcessingContext m_Context`

- `Camera m_Camera`

- `PostProcessingProfile m_PreviousProfile`

- `Boolean m_RenderingInSceneView`

- `BuiltinDebugViewsComponent m_DebugViews`

- `AmbientOcclusionComponent m_AmbientOcclusion`

- `ScreenSpaceReflectionComponent m_ScreenSpaceReflection`

- `FogComponent m_FogComponent`

- `MotionBlurComponent m_MotionBlur`

- `TaaComponent m_Taa`

- `EyeAdaptationComponent m_EyeAdaptation`

- `DepthOfFieldComponent m_DepthOfField`

- `BloomComponent m_Bloom`

- `ChromaticAberrationComponent m_ChromaticAberration`

- `ColorGradingComponent m_ColorGrading`

- `UserLutComponent m_UserLut`

- `GrainComponent m_Grain`

- `VignetteComponent m_Vignette`

- `DitheringComponent m_Dithering`

- `FxaaComponent m_Fxaa`


## Methods

- `Void OnEnable()`

- `Void OnPreCull()`

- `Void OnPreRender()`

- `Void OnPostRender()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`

- `Void OnGUI()`

- `Void OnDisable()`

- `Void ResetTemporalEffects()`

- `Void CheckObservers()`

- `Void DisableComponents()`

- `CommandBuffer AddCommandBuffer(CameraEvent, String)`

- `Void RemoveCommandBuffer()`

- `CommandBuffer GetCommandBuffer(CameraEvent, String)`

- `Void TryExecuteCommandBuffer(PostProcessingComponentCommandBuffer`1)`

- `Boolean TryPrepareUberImageEffect(PostProcessingComponentRenderTexture`1, Material)`

- `T AddComponent(T)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityEngine.PostProcessing
public class PostProcessingBehaviour : MonoBehaviour
{
	public PostProcessingProfile profile; // 0x18
	public Func`2 jitteredMatrixFunc; // 0x20
	private Dictionary`2 m_CommandBuffers; // 0x28
	private List`1 m_Components; // 0x30
	private Dictionary`2 m_ComponentStates; // 0x38
	private MaterialFactory m_MaterialFactory; // 0x40
	private RenderTextureFactory m_RenderTextureFactory; // 0x48
	private PostProcessingContext m_Context; // 0x50
	private Camera m_Camera; // 0x58
	private PostProcessingProfile m_PreviousProfile; // 0x60
	private Boolean m_RenderingInSceneView; // 0x68
	private BuiltinDebugViewsComponent m_DebugViews; // 0x70
	private AmbientOcclusionComponent m_AmbientOcclusion; // 0x78
	private ScreenSpaceReflectionComponent m_ScreenSpaceReflection; // 0x80
	private FogComponent m_FogComponent; // 0x88
	private MotionBlurComponent m_MotionBlur; // 0x90
	private TaaComponent m_Taa; // 0x98
	private EyeAdaptationComponent m_EyeAdaptation; // 0xa0
	private DepthOfFieldComponent m_DepthOfField; // 0xa8
	private BloomComponent m_Bloom; // 0xb0
	private ChromaticAberrationComponent m_ChromaticAberration; // 0xb8
	private ColorGradingComponent m_ColorGrading; // 0xc0
	private UserLutComponent m_UserLut; // 0xc8
	private GrainComponent m_Grain; // 0xd0
	private VignetteComponent m_Vignette; // 0xd8
	private DitheringComponent m_Dithering; // 0xe0
	private FxaaComponent m_Fxaa; // 0xe8
	private List`1 m_ComponentsToEnable; // 0xf0
	private List`1 m_ComponentsToDisable; // 0xf8


	// RVA: 0x6673628 VA: 0x7598c8b628
	private Void OnEnable() { }
	// RVA: 0x6673f1c VA: 0x7598c8bf1c
	private Void OnPreCull() { }
	// RVA: 0x6674aa0 VA: 0x7598c8caa0
	private Void OnPreRender() { }
	// RVA: 0x6674bd8 VA: 0x7598c8cbd8
	private Void OnPostRender() { }
	// RVA: 0x6674cdc VA: 0x7598c8ccdc
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x667536c VA: 0x7598c8d36c
	private Void OnGUI() { }
	// RVA: 0x66754f4 VA: 0x7598c8d4f4
	private Void OnDisable() { }
	// RVA: 0x6675800 VA: 0x7598c8d800
	public Void ResetTemporalEffects() { }
	// RVA: 0x667465c VA: 0x7598c8c65c
	private Void CheckObservers() { }
	// RVA: 0x66744e8 VA: 0x7598c8c4e8
	private Void DisableComponents() { }
	// RVA: 0x VA: 0x0
	private CommandBuffer AddCommandBuffer(CameraEvent evt, String name) { }
	// RVA: 0x VA: 0x0
	private Void RemoveCommandBuffer() { }
	// RVA: 0x VA: 0x0
	private CommandBuffer GetCommandBuffer(CameraEvent evt, String name) { }
	// RVA: 0x VA: 0x0
	private Void TryExecuteCommandBuffer(PostProcessingComponentCommandBuffer`1 component) { }
	// RVA: 0x VA: 0x0
	private Boolean TryPrepareUberImageEffect(PostProcessingComponentRenderTexture`1 component, Material material) { }
	// RVA: 0x VA: 0x0
	private T AddComponent(T component) { }
	// RVA: 0x6675840 VA: 0x7598c8d840
	public Void .ctor() { }
}
```