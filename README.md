# Repositorios OCA

Superproyecto que agrupa **170 repositorios** de la [OCA (Odoo Community Association)](https://github.com/OCA) como **git submodules**, todos anclados a la rama **`19.0`**.

## Cómo usar este repositorio

Clonar incluyendo todos los submódulos:

```bash
git clone --recurse-submodules git@github.com:RodrigoBM/repositorios-oca.git
```

Si ya lo clonaste sin submódulos:

```bash
git submodule update --init --recursive
```

Actualizar todos los submódulos a la última versión de su rama:

```bash
git submodule update --remote --merge
```

## Índice

- [Contabilidad y finanzas](#contabilidad-y-finanzas)
- [Banca, pagos y cobros](#banca-pagos-y-cobros)
- [Localización e impuestos](#localización-e-impuestos)
- [Conectores e integraciones](#conectores-e-integraciones)
- [Ventas, CRM y contratos](#ventas-crm-y-contratos)
- [Compras](#compras)
- [Recursos Humanos](#recursos-humanos)
- [Logística, almacén y distribución](#logística-almacén-y-distribución)
- [Fabricación y producto](#fabricación-y-producto)
- [Proyectos y gestión](#proyectos-y-gestión)
- [Servicios y verticales](#servicios-y-verticales)
- [Web y comercio electrónico](#web-y-comercio-electrónico)
- [Servidor, desarrollo y herramientas](#servidor-desarrollo-y-herramientas)
- [Comunicación y colaboración](#comunicación-y-colaboración)
- [Datos, IA y varios](#datos-ia-y-varios)
- [Plataforma Odoo y migración](#plataforma-odoo-y-migración)

---

## Contabilidad y finanzas

| Repositorio | Descripción |
| --- | --- |
| `account-analytic` | Contabilidad analítica y centros de coste/beneficio. |
| `account-budgeting` | Gestión de presupuestos. |
| `account-closing` | Herramientas de cierre contable y periodificación. |
| `account-consolidation` | Consolidación de balances de varias compañías. |
| `account-financial-reporting` | Informes financieros (balance, pérdidas y ganancias, etc.). |
| `account-financial-tools` | Utilidades y herramientas financieras para contabilidad. |
| `account-fiscal-rule` | Gestión de impuestos y reglas fiscales. |
| `account-invoice-reporting` | Informes de facturación. |
| `account-invoicing` | Extensiones de facturación (rectificativas, agrupaciones, etc.). |
| `account-payment` | Extensión de pagos (proyecto del PSC de banca). |
| `account-reconcile` | Conciliación contable y bancaria. |
| `mis-builder` | Constructor de informes personalizados (P&L, balance, etc.). |
| `mis-builder-contrib` | Módulos adicionales para MIS Builder (incubadora). |
| `margin-analysis` | Control financiero de márgenes y costes. |

## Banca, pagos y cobros

| Repositorio | Descripción |
| --- | --- |
| `bank-payment` | Pagos electrónicos y SEPA. |
| `bank-payment-alternative` | Enfoque alternativo de pagos basado en métodos nativos de Odoo. |
| `bank-statement-import` | Importación de extractos bancarios. |
| `credit-control` | Control de crédito y gestión de cobros. |

## Localización e impuestos

| Repositorio | Descripción |
| --- | --- |
| `l10n-spain` | Localización española (IVA, AEAT, informes fiscales). |
| `intrastat-extrastat` | Declaraciones Intrastat/Extrastat. |

## Conectores e integraciones

| Repositorio | Descripción |
| --- | --- |
| `connector` | Framework genérico de conectores (colas, tareas asíncronas, canales). |
| `connector-accountedge` | Conexión con AccountEdge (MyOB). |
| `connector-cmis` | Conexión con gestores documentales CMIS. |
| `connector-ecommerce` | Base genérica para integraciones de e-commerce. |
| `connector-infor` | Integración con Infor. |
| `connector-interfaces` | Conectores genéricos (ODBC, CSV, etc.). |
| `connector-jira` | Conexión con Jira. |
| `connector-lengow` | Conexión con Lengow (marketplaces). |
| `connector-lims` | Conexión con sistemas de laboratorio (LIMS). |
| `connector-magento` | Conexión con Magento. |
| `connector-mautic` | Conexión con Mautic (marketing). |
| `connector-odoo2odoo` | Sincronización entre instancias Odoo. |
| `connector-prestashop` | Conexión con PrestaShop. |
| `connector-redmine` | Conexión con Redmine. |
| `connector-sage` | Conexión con Sage. |
| `connector-salesforce` | Conexión con Salesforce. |
| `connector-shopify` | Conexión con Shopify. |
| `connector-spscommerce` | Conexión con SPS Commerce (EDI). |
| `connector-telephony` | Integración telefónica (Asterisk, etc.). |
| `connector-woocommerce` | Conexión con WooCommerce. |
| `edi` | Base para intercambio electrónico de datos. |
| `edi-ediversa` | EDI con el proveedor ediversa. |
| `edi-framework` | Framework para implementar EDI. |
| `edi-voxel` | EDI con Voxel. |
| `interface-git` | Interacción con GitHub desde Odoo. |
| `version-control-platform` | Integración con plataformas de control de versiones. |
| `shoppingfeed` | Integración con ShoppingFeed (marketplaces). |
| `dotnet` | Addons escritos en .NET. |

## Ventas, CRM y contratos

| Repositorio | Descripción |
| --- | --- |
| `sale-blanket` | Pedidos marco/blanco con entregas programadas. |
| `sale-channel` | Canales y orígenes de venta. |
| `sale-financial` | Extensiones financieras de ventas. |
| `sale-prebook` | Preventa/compromiso anticipado de pedidos. |
| `sale-promotion` | Promociones y descuentos. |
| `sale-reporting` | Informes de ventas. |
| `sale-workflow` | Flujo y organización de ventas. |
| `crm` | Mejoras de CRM, correo y newsletter. |
| `contract` | Contratos recurrentes con facturación periódica. |
| `partner-contact` | Mejoras de contactos y empresas. |
| `agreement` | Gestión de acuerdos y su ciclo de vida. |
| `commission` | Gestión de comisiones. |
| `sign` | Firma electrónica de documentos. |

## Compras

| Repositorio | Descripción |
| --- | --- |
| `purchase-reporting` | Informes de compras. |
| `purchase-workflow` | Flujo y organización de compras. |

## Recursos Humanos

| Repositorio | Descripción |
| --- | --- |
| `hr` | Mejoras de recursos humanos. |
| `hr-attendance` | Control de asistencia y presencia. |
| `hr-expense` | Gestión de gastos de empleados. |
| `hr-holidays` | Vacaciones, permisos y ausencias. |
| `payroll` | Gestión de nóminas. |
| `timesheet` | Partes de horas. |
| `resource` | Gestión de recursos y calendarios. |

## Logística, almacén y distribución

| Repositorio | Descripción |
| --- | --- |
| `stock-logistics-availability` | Información ampliada de disponibilidad de stock. |
| `stock-logistics-barcode` | Operaciones logísticas con códigos de barras. |
| `stock-logistics-interfaces` | Interfaces entre módulos logísticos. |
| `stock-logistics-orderpoint` | Reglas de reabastecimiento/punto de pedido. |
| `stock-logistics-putaway` | Estrategias de ubicación (putaway). |
| `stock-logistics-release-channel` | Canales de salida/liberación de stock. |
| `stock-logistics-reporting` | Informes logísticos. |
| `stock-logistics-request` | Solicitudes internas de stock. |
| `stock-logistics-reservation` | Reservas de stock. |
| `stock-logistics-shopfloor` | Operaciones de planta/almacén. |
| `stock-logistics-tracking` | Trazabilidad y gestión de paquetes. |
| `stock-logistics-transport` | Gestión de transporte. |
| `stock-logistics-warehouse` | Gestión de almacén. |
| `stock-logistics-workflow` | Flujo y organización de stock. |
| `stock-weighing` | Pesaje de mercancía. |
| `wms` | Sistema de gestión de almacén avanzado. |
| `delivery-carrier` | Transportistas y gestión de envíos. |
| `ddmrp` | Planificación de materiales orientada por demanda (DDMRP). |
| `rma` | Autorización de devolución de mercancía. |
| `route-planning` | Planificación de rutas. |
| `barcode-interface` | Interfaz con lectores de códigos de barras. |
| `shopfloor-app` | Aplicación de operaciones de planta. |

## Fabricación y producto

| Repositorio | Descripción |
| --- | --- |
| `manufacture` | Mejoras de fabricación/MRP. |
| `manufacture-reporting` | Informes de fabricación. |
| `repair` | Órdenes de reparación. |
| `product-attribute` | Atributos y valores de producto. |
| `product-configurator` | Configurador avanzado de productos. |
| `product-kitting` | Gestión de kits de producto. |
| `product-pack` | Packs y combinaciones de productos. |
| `product-variant` | Extensiones de variantes de producto. |
| `odoo-pim` | Gestión de información de producto (PIM). |

## Proyectos y gestión

| Repositorio | Descripción |
| --- | --- |
| `project` | Gestión de proyectos y empresas de servicios. |
| `project-agile` | Metodologías ágiles (Scrum/Kanban). |
| `project-reporting` | Informes de proyectos. |
| `program` | Gestión de programas (conjuntos de proyectos). |
| `operating-unit` | Unidades operativas para segmentar la contabilidad. |
| `department` | Gestión y segmentación por departamentos. |
| `business-requirement` | Gestión de requisitos de negocio. |
| `management-system` | Sistemas de gestión (ISO, IEC, BS). |
| `tier-validation` | Validaciones y aprobaciones por niveles. |
| `multi-company` | Utilidades para operar con múltiples compañías. |
| `role-policy` | Políticas de acceso basadas en rol. |

## Servicios y verticales

| Repositorio | Descripción |
| --- | --- |
| `field-service` | Gestión de servicio técnico de campo. |
| `fleet` | Gestión de flota de vehículos. |
| `maintenance` | Mantenimiento de equipos e instalaciones. |
| `helpdesk` | Sistema de tickets de soporte. |
| `pms` | Property Management System (gestión hotelera). |
| `e-learning` | Plataforma de formación online. |
| `cooperative` | Funcionalidades para cooperativas. |
| `donation` | Gestión de donaciones. |
| `crowdfunding` | Campañas de financiación colectiva. |
| `shift-planning` | Planificación de turnos. |
| `wallet` | Cartera/billetera de puntos o créditos. |

## Web y comercio electrónico

| Repositorio | Descripción |
| --- | --- |
| `web` | Mejoras de la interfaz web/backend. |
| `website` | Extensiones del constructor de sitios web. |
| `website-cms` | Funciones CMS para el sitio web. |
| `website-themes` | Temas para el sitio web. |
| `brand` | Gestión de marcas para productos y compañías. |
| `web-api` | API web. |
| `web-api-contrib` | Contribuciones a la API web. |
| `webhook` | Consumidores de webhooks (GitLab, Bitbucket, etc.). |
| `webkit-tools` | Herramientas de generación de informes HTML/PDF. |
| `pwa-builder` | Constructor de aplicaciones web progresivas (PWA). |
| `e-commerce` | Automatización del e-commerce nativo. |
| `search-engine` | Motor de búsqueda del sitio. |
| `pos` | Punto de venta. |

## Servidor, desarrollo y herramientas

| Repositorio | Descripción |
| --- | --- |
| `server-auth` | Autenticación (OAuth, LDAP, etc.). |
| `server-backend` | Utilidades de backend. |
| `server-brand` | Personalización de marca en el servidor. |
| `server-env` | Gestión de configuración dependiente del entorno. |
| `server-tools` | Utilidades técnicas para administradores de Odoo. |
| `server-ux` | Mejoras de experiencia de usuario en el backend. |
| `rest-api` | API REST. |
| `rest-framework` | Framework para construir APIs REST. |
| `reporting-engine` | Motor de informes alternativo. |
| `report-print-send` | Impresión y envío de informes. |
| `storage` | Almacenamiento externo (S3, Azure, etc.). |
| `queue` | Cola de trabajos asíncronos. |
| `automation` | Automatización de acciones. |
| `cim` | Integración de sistemas de fabricación (CIM). |
| `module-composition-analysis` | Análisis y exploración de repositorios de módulos. |
| `apps-store` | Módulo de la tienda de apps de la OCA. |

## Comunicación y colaboración

| Repositorio | Descripción |
| --- | --- |
| `mail` | Mejoras del sistema de correo. |
| `calendar` | Extensiones de calendario. |
| `event` | Gestión de eventos. |
| `survey` | Encuestas y formularios. |
| `knowledge` | Gestión documental y de conocimiento. |
| `dms` | Sistema de gestión documental (carpetas, versiones). |
| `social` | Redes sociales y mensajería. |
| `mass-mailing` | Envíos de correo masivo. |
| `spreadsheet` | Integración con hojas de cálculo. |

## Datos, IA y varios

| Repositorio | Descripción |
| --- | --- |
| `ai` | Módulos de inteligencia artificial. |
| `currency` | Gestión de divisas y tipos de cambio. |
| `community-data-files` | Datos comunes usados por la comunidad. |
| `data-protection` | Protección de datos (RGPD). |
| `geospatial` | Funcionalidades GIS/geográficas. |
| `iot` | Conexión con dispositivos IoT. |
| `infrastructure` | Gestión de infraestructura de red (DNS, etc.). |

## Plataforma Odoo y migración

| Repositorio | Descripción |
| --- | --- |
| `OCB` | Odoo Community Backports (fork de Odoo mantenido por la comunidad). |
| `OpenUpgrade` | Ruta de migración entre versiones de Odoo/OpenERP. |
