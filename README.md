# Guía de Integración UI: Electrónica 2001
Este documento define cómo la interfaz debe interpretar las respuestas del servidor para asegurar la consistencia de los datos en el frontend.

Las respuestas están estandarizadas en formato JSON para simplificar su consumo. El objeto resultante contiene todas las propiedades y rutas requeridas para renderizar completamente la interfaz del producto sin necesidad de peticiones adicionales.

# Respuestas de nuestra API 
## Información de producto

```json
{
	"ok": true,
	"message": "Productos encontrados correctamente.",
	"data": {
		"id": 7016,
		"sku": "001-902IM",
		"name": "115998:IM GUIT. ELECT. SE NF3 ICE BLUE MN C/GIG BAG PRS",
		"slug": "115998-im-guit-elect-se-nf3-ice-blue-mn-c-gig-bag-prs-001-902im",
		"price": 999,
		"discount": 0,
		"final_price": 999,
		"description": "La PRS SE NF 3 es una guitarra eléctrica versátil diseñada para ser el caballo de batalla de cualquier músico. Basada en la estética clásica del estilo 'S', esta guitarra fusiona la tradición del rock 'n' roll con la innovación moderna de PRS. Su cuerpo de álamo (poplar) ofrece una base tonal equilibrada y resonante, mientras que el mástil y el diapasón de arce (maple) aportan calidez, brillo y una articulación excepcional en cada registro. El corazón de este instrumento es su trío de pastillas Narrowfield DD 'S'. Estas pastillas son verdaderos camaleones sonoros, capaces de capturar la potencia de un humbucker, la mordida de una P-90 y la claridad de una bobina simple (single-coil), todo sin sacrificar un enfoque sónico nítido. Con un mástil de perfil Wide Thin extremadamente rápido, un radio de 10 pulgadas y el confiable trémolo patentado de PRS, la SE NF 3 está construida para una expresión máxima, permitiéndote navegar desde tonos suaves y melódicos hasta distorsiones potentes con total comodidad.",
		"images": [
			{
				"url": "https://electronica2001es.com/action-dash/../images/2023/20260106230321_.jpg",
				"alt_text": "001-902IM",
				"display_order": 0,
				"is_primary": false
			},
			{
				"url": "https://electronica2001es.com/action-dash/../images/2023/20260106230321.jpg",
				"alt_text": "001-902IM",
				"display_order": 1,
				"is_primary": true
			}
		],
		"brand": {
			"id": 76,
			"name": "PRS",
			"slug": "prs",
			"logo_url": "https://upload.wikimedia.org/wikipedia/commons/6/6e/Prs_guitars_logo.png",
			"website": null,
			"is_active": true
		},
		"category": {
			"id": 129,
			"name": "Guitarra Electrica",
			"slug": "guitarra-electrica",
			"parent_id": 1,
			"image_url": null,
			"is_active": true
		},
		"warehouse": [
			{
				"warehouse": "AHUACHAPAN",
				"stock": 0
			},
			{
				"warehouse": "CASA MATRIZ",
				"stock": 0
			},
			{
				"warehouse": "ESCALON",
				"stock": 6
			},
			{
				"warehouse": "PLAZA MORAZAN",
				"stock": 0
			},
			{
				"warehouse": "SAN MIGUEL",
				"stock": 0
			},
			{
				"warehouse": "SANTA ANA",
				"stock": 0
			},
			{
				"warehouse": "SONSONATE",
				"stock": 0
			}
		],
		"specs": {
			"Body": [
				{
					"Body Type": "Solidbody"
				},
				{
					"Body Shape": "SE NF 3"
				},
				{
					"Body Material": "Poplar"
				},
				{
					"Body Finish": "High Gloss Poly"
				},
				{
					"Color": "Ice Blue Metallic"
				}
			],
			"Neck": [
				{
					"Neck Material": "Maple"
				},
				{
					"Neck Shape": "SE Wide Thin"
				},
				{
					"Neck Joint": "Bolt-on"
				},
				{
					"Radius": "10\""
				},
				{
					"Fingerboard Material": "Maple"
				},
				{
					"Fingerboard Inlay": "Birds"
				},
				{
					"Number of Frets": "22"
				},
				{
					"Scale Length": "25\""
				},
				{
					"Nut Width": "1.6875\""
				},
				{
					"Nut Material": "PRS Proprietary"
				}
			],
			"General": [
				{
					"Number of Strings": "6"
				},
				{
					"Left-/Right-handed": "Right-handed"
				}
			],
			"Hardware": [
				{
					"Bridge/Tailpiece": "PRS Patented Tremolo"
				},
				{
					"Tuners": "PRS Designed, 18:1"
				}
			],
			"Electronics": [
				{
					"Neck Pickup": "PRS Narrowfield DD \"S\" Humbucker"
				},
				{
					"Middle Pickup": "PRS Narrowfield DD \"S\" Humbucker"
				},
				{
					"Bridge Pickup": "PRS Narrowfield DD \"S\" Humbucker"
				},
				{
					"Controls": "1 x volume, 1 x tone"
				},
				{
					"Switching": "5-way blade pickup switch"
				}
			],
			"Miscellaneous": [
				{
					"Strings": "PRS Classic, .010-.046"
				},
				{
					"Case/Gig Bag": "Gig Bag"
				},
				{
					"Manufacturer Part Number": "115998::IM"
				},
				{
					"Serial Number": "CTIH055256"
				}
			]
		},
		"tags": [
			"guitarra-electrica-s-style",
			"pastillas-narrowfield",
			"prs-se-series",
			"cuerdas-guitarra-electrica",
			"estuche-para-guitarra-electrica",
			"amplificador-para-guitarra-electrica",
			"cable-para-instrumento-1/4",
			"mantenimiento-de-guitarra",
			"afinador-pedal-o-clip",
			"tahali-para-guitarra",
			"repuestos-prs"
		],
		"sibling_products": [
			{
				"id": 3691,
				"sku": "001-180VS",
				"name": "100468:VS CU2 GUIT. ELECT. SE CUSTOM 22 VINTAGE SUNBURST C/GIG BAG PRS",
				"slug": "100468-vs-cu2-guit-elect-se-custom-22-vintage-sunburst-c-gig-bag-prs-001-180vs",
				"image": "https://electronica2001es.com/images/2021/PRS2021/001180VS/1.jpg",
				"price": 1050,
				"similarity_score": "100",
				"shared_tags_count": null,
				"businessScore": 100,
				"isInPriceRange": true
			},
			{
				"id": 3687,
				"sku": "001-177VC",
				"name": "108116:VC ST4 GUIT. ELECT. SE STANDARD 24 VINTAGE CHERRY C/GIG BAG PRS",
				"slug": "108116-vc-st4-guit-elect-se-standard-24-vintage-cherry-c-gig-bag-prs-001-177vc",
				"image": "https://electronica2001es.com/images/2021/PRS2021/001177VC/1.jpg",
				"price": 950,
				"similarity_score": "100",
				"shared_tags_count": null,
				"businessScore": 100,
				"isInPriceRange": true
			},
			{
				"id": 3688,
				"sku": "001-178TS",
				"name": "108117:TS ST245 GUIT. ELECT. SE STANDARD 245 TOBACCO SUNBURST C/GIG BAG PRS",
				"slug": "108117-ts-st245-guit-elect-se-standard-245-tobacco-sunburst-c-gig-bag-prs-001-178ts",
				"image": "https://electronica2001es.com/images/2021/PRS2021/001178TS/1.jpg",
				"price": 950,
				"similarity_score": "100",
				"shared_tags_count": null,
				"businessScore": 100,
				"isInPriceRange": true
			},
			{
				"id": 3689,
				"sku": "001-179VC",
				"name": "105629:VC MI GUIT. ELECT. SE MIRA BEVELED VINTAGE CHERRY C/GIG BAG PRS",
				"slug": "105629-vc-mi-guit-elect-se-mira-beveled-vintage-cherry-c-gig-bag-prs-001-179vc",
				"image": "https://electronica2001es.com/images/2021/PRS2021/001179VC/1.jpg",
				"price": 799,
				"similarity_score": "100",
				"shared_tags_count": null,
				"businessScore": 100,
				"isInPriceRange": true
			},
			{
				"id": 3690,
				"sku": "001-180SA",
				"name": "100468:SA CU2 GUIT. ELECT. SE CUSTOM 22 SAPHIRE BLACK C/GIG BAG PRS",
				"slug": "100468-sa-cu2-guit-elect-se-custom-22-saphire-black-c-gig-bag-prs-001-180sa",
				"image": "https://electronica2001es.com/images/2021/PRS2021/001180SA/1.jpg",
				"price": 1050,
				"similarity_score": "100",
				"shared_tags_count": null,
				"businessScore": 100,
				"isInPriceRange": true
			},
			{
				"id": 3692,
				"sku": "001-181BG",
				"name": "107993:BG CU44 GUIT. ELECT. SE CUSTOM 24 BLACK GOLD C/GIG BAG PRS",
				"slug": "107993-bg-cu44-guit-elect-se-custom-24-black-gold-c-gig-bag-prs-001-181bg",
				"image": "https://electronica2001es.com/images/2021/PRS2021/001181BG/1.jpg",
				"price": 1075,
				"similarity_score": "100",
				"shared_tags_count": null,
				"businessScore": 100,
				"isInPriceRange": true
			}
		],
		"related_by_tags": [
            // NOTA: Datos de prueba. Este arreglo de productos relacionados es temporal y no sigue las reglas de negocio ni el algoritmo de vinculación por tags definido para producción.
            {
				"id": 3692,
				"sku": "001-181BG",
				"name": "107993:BG CU44 GUIT. ELECT. SE CUSTOM 24 BLACK GOLD C/GIG BAG PRS",
				"slug": "107993-bg-cu44-guit-elect-se-custom-24-black-gold-c-gig-bag-prs-001-181bg",
				"image": "https://electronica2001es.com/images/2021/PRS2021/001181BG/1.jpg",
				"price": 1075,
				"similarity_score": "100",
				"shared_tags_count": null,
				"businessScore": 100,
				"isInPriceRange": true
			}
        ],
		"execution_time": "260.16ms"
	}
}
```

## Productos (Busqueda de productos) 
### ?q=fender stratocaster&l=24

```javascript
{
	"ok": true,
	"message": "Productos encontrados correctamente.",
	"data": {
		"execution_time": "614ms",
		"count": 70,
		"pages": 3,
		"products": [
			{
				"id": 6565,
				"sku": "083-367",
				"name": "0056254049 SET DE PERILLAS ORIGINALES VOLUMEN (1) / TONO (2) P/ STRATOCASTER FENDER",
				"slug": "0056254049-set-de-perillas-originales-volumen-1-tono-2-p-stratocaster-fender-083-367",
				"price": 11,
				"discount": 0,
				"final_price": 11,
				"images": [
					{
						"url": "https://electronica2001es.com/action-dash/../images/2023/20250303161848.jpg",
						"alt_text": "083-367",
						"display_order": 1,
						"is_primary": true
					}
				],
				"brand": {
					"name": "Fender",
					"slug": "fender",
					"logo_url": "https://electronica2001es.com/2020/img/marcas/12.png"
				},
				"disponibility": [
					{
						"warehouse": "AHUACHAPAN",
						"stock": 2
					},
					{
						"warehouse": "CASA MATRIZ",
						"stock": 2
					},
					{
						"warehouse": "ESCALON",
						"stock": 7
					},
					{
						"warehouse": "PLAZA MORAZAN",
						"stock": 3
					},
					{
						"warehouse": "SAN MIGUEL",
						"stock": 2
					},
					{
						"warehouse": "SANTA ANA",
						"stock": 2
					},
					{
						"warehouse": "SONSONATE",
						"stock": 2
					}
				],
				"search_rank": 11.28378376364708
			}, ...],
            "filters": {
			"min_price": 11,
			"max_price": 3500,
			"brands": [
				{
					"id": 12,
					"name": "Fender",
					"slug": "fender",
					"logo_url": "https://electronica2001es.com/2020/img/marcas/12.png",
					"count": 70
				}
			],
			"categories": [
				{
					"id": 80,
					"name": "Clavijas",
					"slug": "clavijas",
					"count": 2
				},
				{
					"id": 114,
					"name": "Estuche Guitarra",
					"slug": "estuche-guitarra",
					"count": 1
				},
				{
					"id": 129,
					"name": "Guitarra Electrica",
					"slug": "guitarra-electrica",
					"count": 60
				},
				{
					"id": 154,
					"name": "Microfonia",
					"slug": "microfonia",
					"count": 4
				},
				{
					"id": 167,
					"name": "Otros Accesorios",
					"slug": "otros-accesorios",
					"count": 1
				},
				{
					"id": 211,
					"name": "Repuestos Varios",
					"slug": "repuestos-varios",
					"count": 2
				}
			]
		}
	}
}
```

## Creación de usuario (Registro)
Notas: 
1. Validación de Credenciales
Por motivos de seguridad y cumplimiento de protocolos de privacidad, el campo password no es retornado por la API. No obstante, el formulario de registro debe implementar obligatoriamente un sistema de confirmación de contraseña ("Contraseña" y "Confirmar Contraseña").

2. Normalización de Datos de Contacto
Para la captura del número telefónico, se debe integrar un selector de prefijo internacional (phone_code). Esto garantiza la correcta segmentación geográfica y la validez de los datos para futuras comunicaciones o envíos.

3. Protocolo de Verificación OTP (One-Time Password)
Una vez completado el registro, el sistema requerirá la activación de la cuenta mediante un código de verificación de 6 dígitos enviado vía correo electrónico.

Requerimiento de UI: Es indispensable diseñar una vista específica para la validación del Código OTP.

Funcionalidad: La interfaz debe permitir el ingreso secuencial de los 6 dígitos y ofrecer la opción de "Reenviar código" tras un tiempo de espera definido.

```json
{
	"ok": true,
	"message": "Registro de usuario exitoso.",
	"data": {
		"uuid": "5dd70a94-0ea8-42af-8e45-305de1bee5aa",
		"first_name": "John",
		"last_name": "Doe",
		"email": "johndue@gmail.com",
		"phone": "+50370001234",
		"avatar_url": null,
		"email_verified_at": null
	}
}
```

## Categorias relación de 1 a N

| Categoría Padre | Categoría Hija |
| :--- | :--- |
| Audio Profesional | Amplificadores |
| Amplificadores | Amplificador de audio |

```json
{
	"ok": true,
	"message": "Categorías encontradas correctamente.",
	"data": [
		{
			"id": 1,
			"name": "Instrumentos Musicales",
			"slug": "instrumentos-musicales",
			"parent_id": null,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 2,
			"name": "Audio Profesional",
			"slug": "audio-profesional",
			"parent_id": null,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 3,
			"name": "Repuestos y Electronica",
			"slug": "repuestos-y-electronica",
			"parent_id": null,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 4,
			"name": "Iluminacion",
			"slug": "iluminacion",
			"parent_id": null,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 5,
			"name": "Accesorios",
			"slug": "accesorios",
			"parent_id": null,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 6,
			"name": "Afinadores",
			"slug": "afinadores",
			"parent_id": 5,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 7,
			"name": "Agarraderas",
			"slug": "agarraderas",
			"parent_id": 5,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 8,
			"name": "Agogo",
			"slug": "agogo",
			"parent_id": 5,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 9,
			"name": "Alfombras",
			"slug": "alfombras",
			"parent_id": 5,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 10,
			"name": "Amplificadores",
			"slug": "amplificadores",
			"parent_id": 2,
			"image_url": null,
			"is_active": true
		},
		{
			"id": 11,
			"name": "Amplificador de audio",
			"slug": "amplificador-de-audio",
			"parent_id": 10,
			"image_url": null,
			"is_active": true
		},
       ...
    ]
}
```
## Información de usuario (Perfil)
```json
{
	"ok": true,
	"message": "Usuario encontrado exitosamente.",
	"data": {
		"uuid": "5dd70a94-0ea8-42af-8e45-305de1bee5aa",
		"email": "johndoe@gmail.com",
		"first_name": "John",
		"last_name": "Doe",
		"phone": "+50370001234",
		"avatar_url": null,
		"email_verified_at": "2026-01-27T00:11:42.436Z",
		"addresses": [
			{
				"uuid": "4eeb60a2-805b-4eb5-a43c-14195c435727",
				"alias": "Casa",
				"department": "San Salvador",
				"city": "San Salvador",
				"address_line": "Colonia Escalón, Calle El Mirador, #45",
				"reference_point": "Portón negro, frente al parque de la colonia",
				"latitude": "13.70132660",
				"longitude": "-89.22443390",
				"is_default": true,
				"country": "El Salvador"
			},
			{
				"uuid": "64f7b8be-5562-4e4c-94ab-11f78f5a4ac3",
				"alias": "Casa",
				"department": "San Salvador",
				"city": "San Salvador",
				"address_line": "39 Avenida sur colonia monserrat",
				"reference_point": "Portón negro, frente al parque de la colonia",
				"latitude": "13.70132660",
				"longitude": "-89.22443390",
				"is_default": true,
				"country": "El Salvador"
			},
			{
				"uuid": "c906127f-09d6-4a2d-829c-e44b96388806",
				"alias": "Casa 2",
				"department": "San Salvador",
				"city": "San Salvador",
				"address_line": "39 Avenida sur colonia monserrat",
				"reference_point": "Portón negro, frente al parque de la colonia",
				"latitude": "13.70132660",
				"longitude": "-89.22443390",
				"is_default": false,
				"country": "El Salvador"
			}
		]
	}
}
```
# 🛒 INFORMACIÓN DE COMPRA

### 🔹 Datos de Contacto y Pago
* **Email:**
* **Método de Pago:**
* **Selección de sucursal:**
* **Tipo de Documento:** (CF / CCF)

---

### 📄 Datos de Facturación

#### **Si seleccionó Consumidor Final (CF):**
* **Nombre completo:**
* **Número de documento:**

#### **Si seleccionó Crédito Fiscal (CCF):**
* **Nombre:**
* **NRC:**
* **NIT:**
* **Giro:**
* **Dirección de CCF:**
* **Email de CCF:**

---

### 📦 Entrega y Recepción
* **Modalidad:** (Envío a domicilio / Retiro en sucursal)
* **Quién retira o recibe:**
* **Contacto:**
* **Dirección:**
* **Punto de referencia:**
* **Coordenadas (Mapa y puntero):**

El orden puede modificarse para facilitar la comprensión del usuario o el correcto llenado del formulario.
