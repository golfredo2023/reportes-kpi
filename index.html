<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reporte Ejecutivo de KPIs</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
    :root {
        --azul: #0f4bb4;
        --azul-claro: #eef4ff;
        --verde: #15803d;
        --verde-claro: #ecfdf5;
        --rojo: #b91c1c;
        --rojo-claro: #fef2f2;
        --texto: #1e293b;
        --texto-sec: #64748b;
        --borde: #e2e8f0;
        --fondo: #f8fafc;
    }
    * { box-sizing: border-box; }
    body {
        margin: 0;
        padding: 0;
        background: var(--fondo);
        color: var(--texto);
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        font-size: 16px;
        line-height: 1.5;
        -webkit-text-size-adjust: 100%;
    }
    .contenedor {
        max-width: 900px;
        margin: 0 auto;
        padding: 20px 16px 48px;
    }
    header.encabezado {
        margin-bottom: 20px;
    }
    header.encabezado h1 {
        font-size: 1.5rem;
        margin: 0 0 4px;
        color: var(--texto);
    }
    header.encabezado .subtitulo {
        color: var(--texto-sec);
        font-size: 0.9rem;
        margin: 0;
    }
    header.encabezado .consultado {
        color: var(--texto-sec);
        font-size: 0.85rem;
        margin: 6px 0 0;
    }

    /* ---- Resumen ejecutivo (banner superior) ---- */
    .exec-resumen {
        background: linear-gradient(135deg, #0f4bb4 0%, #1d4ed8 100%);
        border-radius: 14px;
        padding: 16px 18px;
        margin-bottom: 22px;
        color: #ffffff;
    }
    .exec-resumen-titulo {
        font-size: 0.78rem;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 0.05em;
        opacity: 0.88;
        margin-bottom: 10px;
    }
    .exec-chips {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
    }
    .exec-chip {
        background: rgba(255, 255, 255, 0.14);
        border-radius: 10px;
        padding: 8px 12px;
        min-width: 126px;
        flex: 1 1 126px;
    }
    .exec-chip-label {
        font-size: 0.64rem;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 0.02em;
        opacity: 0.82;
        margin-bottom: 3px;
        white-space: nowrap;
    }
    .exec-chip-valor {
        font-size: 1.05rem;
        font-weight: 800;
        color: #ffffff;
    }
    .exec-chip-valor.positivo { color: #86efac; }
    .exec-chip-valor.negativo { color: #fca5a5; }

    /* ---- Navegacion rapida por secciones ---- */
    .nav-secciones {
        position: sticky;
        top: 0;
        z-index: 20;
        display: flex;
        gap: 6px;
        overflow-x: auto;
        -webkit-overflow-scrolling: touch;
        padding: 10px 0;
        margin-bottom: 20px;
        background: rgba(248, 250, 252, 0.95);
        border-bottom: 1px solid var(--borde);
    }
    .nav-secciones a {
        flex: 0 0 auto;
        display: inline-flex;
        align-items: center;
        gap: 6px;
        padding: 7px 13px;
        border-radius: 999px;
        background: #ffffff;
        border: 1px solid var(--borde);
        color: var(--texto);
        font-size: 0.74rem;
        font-weight: 700;
        text-decoration: none;
        white-space: nowrap;
    }
    .nav-secciones a:hover,
    .nav-secciones a:active {
        background: var(--azul-claro);
        border-color: var(--azul);
        color: var(--azul);
    }

    .seccion-titulo {
        font-size: 1.05rem;
        font-weight: 800;
        color: var(--texto);
        margin: 34px 0 12px;
        padding-bottom: 6px;
        border-bottom: 2px solid var(--borde);
        display: flex;
        align-items: center;
        gap: 8px;
        scroll-margin-top: 64px;
    }
    .subseccion {
        font-size: 0.85rem;
        font-weight: 700;
        color: var(--texto);
        margin: 18px 0 8px;
    }
    .kpi-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
        gap: 12px;
    }
    .kpi-card {
        background: #ffffff;
        border: 1px solid var(--borde);
        border-radius: 12px;
        padding: 16px;
        box-shadow: 0 1px 2px rgba(15, 23, 42, 0.04);
    }
    .kpi-card .titulo {
        font-size: 0.78rem;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 0.03em;
        color: var(--texto-sec);
        margin: 0 0 8px;
    }
    .kpi-card .valor {
        font-size: 1.9rem;
        font-weight: 800;
        margin: 0 0 8px;
        line-height: 1.1;
    }
    .kpi-card .valor.positivo { color: var(--verde); }
    .kpi-card .valor.negativo { color: var(--rojo); }
    .kpi-card .detalle {
        font-size: 0.82rem;
        color: var(--texto-sec);
        margin: 2px 0;
    }
    .stat-cards {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
        gap: 10px;
    }
    .stat-card {
        background: #ffffff;
        border: 1px solid var(--borde);
        border-radius: 10px;
        padding: 12px 14px;
    }
    .stat-card .titulo {
        font-size: 0.68rem;
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 0.02em;
        color: var(--texto-sec);
        margin: 0 0 6px;
    }
    .stat-card .valor {
        font-size: 1.3rem;
        font-weight: 800;
        margin: 0 0 4px;
        line-height: 1.15;
        color: var(--texto);
    }
    .stat-card .detalle {
        font-size: 0.72rem;
        color: var(--texto-sec);
        margin: 1px 0;
    }
    .stat-card .barra {
        height: 5px;
        background: #e2e8f0;
        border-radius: 3px;
        margin: 7px 0 5px;
        overflow: hidden;
    }
    .stat-card .barra > span {
        display: block;
        height: 100%;
        border-radius: 3px;
    }
    .tabla-wrap {
        overflow-x: auto;
        -webkit-overflow-scrolling: touch;
        border: 1px solid var(--borde);
        border-radius: 10px;
        margin-bottom: 8px;
    }
    table.datos {
        border-collapse: collapse;
        width: 100%;
        min-width: 480px;
        font-size: 0.78rem;
    }
    table.datos th {
        background: var(--th-bg, var(--azul));
        color: #ffffff;
        text-align: left;
        padding: 8px 10px;
        font-size: 0.7rem;
        text-transform: uppercase;
        letter-spacing: 0.02em;
        white-space: nowrap;
        line-height: 1.3;
    }
    table.datos td {
        padding: 6px 10px;
        border-top: 1px solid var(--borde);
        color: var(--texto);
        white-space: nowrap;
    }
    table.datos td .celda-total {
        display: flex;
        align-items: center;
        gap: 8px;
    }
    table.datos td .celda-total .n {
        font-weight: 700;
        min-width: 1.6em;
        text-align: right;
    }
    table.datos td .celda-total .mini-barra {
        flex: 1 1 auto;
        max-width: 70px;
        height: 6px;
        background: #e2e8f0;
        border-radius: 3px;
        overflow: hidden;
    }
    table.datos td .celda-total .mini-barra > span {
        display: block;
        height: 100%;
        border-radius: 3px;
    }
    table.datos tbody tr:hover td {
        background: #f8fafc;
    }
    table.datos tr.total td {
        font-weight: 800;
        background: var(--azul-claro);
    }
    table.datos tr.destacada td {
        background: #fff9c4;
        font-weight: 700;
    }
    .banner-info {
        background: #f1f5f9;
        border-radius: 8px;
        padding: 10px 14px;
        font-size: 0.8rem;
        color: var(--texto-sec);
        margin-bottom: 10px;
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        gap: 6px;
    }
    .banner-info b {
        color: var(--azul);
        font-size: 0.95rem;
    }
    .summary-cards {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
        gap: 8px;
        margin-bottom: 12px;
    }
    .summary-cards .mini {
        background: #f1f5f9;
        border: 1px solid var(--borde);
        border-radius: 8px;
        padding: 8px 10px;
    }
    .summary-cards .mini .l {
        font-size: 0.65rem;
        font-weight: 700;
        text-transform: uppercase;
        color: var(--texto-sec);
    }
    .summary-cards .mini .v {
        font-size: 1.1rem;
        font-weight: 800;
        color: var(--texto);
    }
    .detalle-labs-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 10px;
        margin-bottom: 10px;
    }
    .detalle-lab-card {
        background: #ffffff;
        border: 1px solid var(--borde);
        border-radius: 10px;
        padding: 12px 14px;
    }
    .detalle-lab-header {
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        gap: 8px;
        font-weight: 700;
        font-size: 0.82rem;
        color: var(--texto);
        padding-bottom: 6px;
        margin-bottom: 6px;
        border-bottom: 1px solid var(--borde);
    }
    .detalle-lab-header .total {
        color: #4338ca;
        font-weight: 800;
        flex-shrink: 0;
    }
    .detalle-lab-lista {
        list-style: none;
        margin: 0;
        padding: 0;
    }
    .detalle-lab-lista li {
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        gap: 10px;
        font-size: 0.76rem;
        padding: 3px 0;
        color: var(--texto);
    }
    .detalle-lab-lista li .nombre {
        color: var(--texto-sec);
    }
    .detalle-lab-lista li .cant {
        font-weight: 700;
        flex-shrink: 0;
    }
    .detalle-lab-lista li.otros .nombre {
        font-style: italic;
    }
    .nota {
        font-size: 0.7rem;
        font-style: italic;
        color: var(--texto-sec);
        margin: 4px 0 0;
    }
    footer.pie {
        margin-top: 40px;
        padding-top: 16px;
        border-top: 1px solid var(--borde);
        font-size: 0.78rem;
        color: var(--texto-sec);
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        gap: 4px;
    }
    .estado-vacio {
        text-align: center;
        color: var(--texto-sec);
        padding: 48px 16px;
    }

    /* ---- Skeleton de carga ---- */
    @keyframes skeletonPulse { 0%, 100% { opacity: 0.45; } 50% { opacity: 0.9; } }
    .sk { background: #e2e8f0; border-radius: 8px; animation: skeletonPulse 1.3s ease-in-out infinite; }
    .sk-title { height: 26px; width: 55%; margin-bottom: 10px; }
    .sk-line { height: 14px; width: 35%; margin-bottom: 26px; }
    .sk-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(210px, 1fr)); gap: 12px; }
    .sk-card { height: 108px; }

    @media (max-width: 560px) {
        .contenedor { padding: 14px 10px 40px; }
        .kpi-card .valor { font-size: 1.6rem; }
        header.encabezado h1 { font-size: 1.3rem; }
        .exec-chip { min-width: 108px; }
        .stat-cards { grid-template-columns: repeat(auto-fit, minmax(135px, 1fr)); gap: 8px; }
        .stat-card { padding: 10px 12px; }
        .stat-card .valor { font-size: 1.15rem; }
        .seccion-titulo { font-size: 0.95rem; margin: 26px 0 10px; }
        .summary-cards { grid-template-columns: repeat(auto-fit, minmax(100px, 1fr)); }
        table.datos { min-width: 440px; font-size: 0.74rem; }
        table.datos th, table.datos td { padding: 6px 8px; }
    }
</style>
</head>
<body>
    <div class="contenedor" id="app">
        <div class="sk sk-title"></div>
        <div class="sk sk-line"></div>
        <div class="sk-cards">
            <div class="sk sk-card"></div>
            <div class="sk sk-card"></div>
            <div class="sk sk-card"></div>
        </div>
    </div>

    <script>
        // Esta pagina se aloja UNA sola vez en un hosting estatico (GitHub
        // Pages) porque Supabase Storage se niega a servir archivos .html con su
        // Content-Type real (los fuerza a text/plain por seguridad, para evitar
        // que contenido subido por usuarios se ejecute como HTML bajo su dominio
        // compartido). Los DATOS de cada reporte si viven en Supabase (como
        // .json, que Supabase sirve correctamente) y esta pagina los pide por
        // fetch() usando el token que viene en su propia URL (?token=...).
        // NOTA: este archivo usa solo caracteres ASCII (entidades HTML para las
        // tildes) a proposito, para evitar problemas de codificacion al copiar y
        // pegar el contenido en el editor web de GitHub.
        const SUPABASE_URL = 'https://zrdlvykhircycpxqjlug.supabase.co';
        // Proyecto anterior: solo como respaldo mientras termina la migracion de cuenta (2026-10).
        const SUPABASE_URL_ANTERIOR = 'https://tbvkfbppzgsgacdyhqcn.supabase.co';
        const SUPABASE_BUCKET = 'ReportesSeguimientoOperativo';

        function formatPct(val) {
            const n = parseFloat(val) || 0;
            const signo = n > 0 ? '+' : '';
            return `${signo}${n.toFixed(2)}%`;
        }

        function claseTendencia(val) {
            return (parseFloat(val) || 0) >= 0 ? 'positivo' : 'negativo';
        }

        function fmtN(n) {
            return (Number(n) || 0).toLocaleString('es-PE');
        }

        function esc(s) {
            if (s === undefined || s === null) return '';
            return String(s).replace(/[&<>"']/g, function (c) {
                return { '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[c];
            });
        }

        function barra(pct, color) {
            if (pct === undefined || pct === null) return '';
            const p = Math.max(0, Math.min(100, Number(pct) || 0));
            return '<div class="barra"><span style="width:' + p + '%; background:' + color + ';"></span></div>';
        }

        function statCard(titulo, valor, detalles, valorColor, pct, barColor) {
            const det = (detalles || []).map(function (d) { return '<p class="detalle">' + d + '</p>'; }).join('');
            const barHtml = barra(pct, barColor || '#3b82f6');
            const style = valorColor ? (' style="color:' + valorColor + ';"') : '';
            return '<div class="stat-card"><p class="titulo">' + titulo + '</p><p class="valor"' + style + '>' + valor + '</p>' + barHtml + det + '</div>';
        }

        // headerColor es opcional (color solido del encabezado, por defecto azul).
        // Los headers[] pueden incluir <br> para apilar palabras en 2 lineas y
        // ahorrar ancho en columnas numericas.
        function tabla(headers, rows, headerColor) {
            const styleAttr = headerColor ? (' style="--th-bg:' + headerColor + ';"') : '';
            const thead = '<tr>' + headers.map(function (h) { return '<th>' + h + '</th>'; }).join('') + '</tr>';
            const tbody = rows.map(function (r) {
                const cls = r._cls ? (' class="' + r._cls + '"') : '';
                const tds = r.cells.map(function (c) { return '<td>' + c + '</td>'; }).join('');
                return '<tr' + cls + '>' + tds + '</tr>';
            }).join('');
            return '<div class="tabla-wrap"><table class="datos"' + styleAttr + '><thead>' + thead + '</thead><tbody>' + tbody + '</tbody></table></div>';
        }

        // Celda de "Total" con mini-barra proporcional al valor maximo de la
        // columna (mismo espiritu que las tablas del PDF de referencia).
        function celdaTotal(valor, maxValor, color) {
            const v = Number(valor) || 0;
            const max = Number(maxValor) || 0;
            const pct = max > 0 ? Math.max(2, Math.round((v / max) * 100)) : 0;
            return '<div class="celda-total"><span class="n">' + fmtN(v) + '</span><span class="mini-barra"><span style="width:' + pct + '%; background:' + (color || '#3b82f6') + ';"></span></span></div>';
        }

        function chipTrend(icon, label, valorPct) {
            const cls = claseTendencia(valorPct);
            const arrow = cls === 'positivo' ? 'fa-arrow-trend-up' : 'fa-arrow-trend-down';
            return '<div class="exec-chip"><div class="exec-chip-label"><i class="fas ' + icon + '"></i> ' + label + '</div><div class="exec-chip-valor ' + cls + '"><i class="fas ' + arrow + '"></i> ' + formatPct(valorPct) + '</div></div>';
        }

        function chipPlain(icon, label, texto) {
            return '<div class="exec-chip"><div class="exec-chip-label"><i class="fas ' + icon + '"></i> ' + label + '</div><div class="exec-chip-valor">' + texto + '</div></div>';
        }

        // Banner "resumen ejecutivo": reutiliza EXACTAMENTE los mismos campos y
        // funciones de formato (formatPct/fmtN) que el resto del reporte, para
        // garantizar que estos numeros nunca puedan desalinearse de los que se
        // muestran mas abajo en detalle.
        function renderResumenEjecutivo(data) {
            const mensual = data.tendencia_mensual || {};
            const semanal = data.tendencia_semanal || {};
            const fc = data.facturacion_cobranzas || {};
            const ef = fc.eficiencia_facturacion || {};
            const ec = fc.eficiencia_cobro || {};

            let html = '<div class="exec-resumen">';
            html += '<div class="exec-resumen-titulo"><i class="fas fa-chart-line"></i> Resumen ejecutivo</div>';
            html += '<div class="exec-chips">';
            html += chipTrend('fa-calendar', 'Acumulado anual', data.crecimiento_ytd);
            html += chipTrend('fa-calendar-day', 'Mes actual', mensual.variacion_porcentual);
            html += chipTrend('fa-calendar-week', 'Semana actual', semanal.variacion_porcentual);
            if (ef.porcentaje !== undefined && ef.porcentaje !== null) {
                html += chipPlain('fa-file-invoice-dollar', 'Efic. facturaci&oacute;n', (ef.porcentaje || 0) + '%');
            }
            if (ec.porcentaje !== undefined && ec.porcentaje !== null) {
                html += chipPlain('fa-hand-holding-dollar', 'Efic. cobro', (ec.porcentaje || 0) + '%');
            }
            html += '</div></div>';
            return html;
        }

        function renderGestionComercial(gc) {
            if (!gc) return '';
            const ing = gc.ingresos || {};
            const pg = gc.proformas_generadas || {};
            const pa = gc.proformas_aceptadas || {};
            const pgest = gc.proformas_gestionadas || {};
            const pef = gc.eficiencia_aprobacion || {};
            const pctAcept = pg.total > 0 ? Math.round((pa.total / pg.total) * 100) : 0;
            const pctFaltaGestion = Math.max(0, 100 - (pgest.pct || 0));
            const pctRechazo = Math.max(0, 100 - (pef.pct || 0));

            let html = '<div class="seccion-titulo" style="color:#0f4bb4;"><i class="fas fa-briefcase"></i> 1. Gesti&oacute;n comercial</div>';
            html += '<div class="stat-cards">';
            html += statCard('Ingresos del d&iacute;a', fmtN(ing.total), [
                'Lab: ' + fmtN(ing.lab) + ' &middot; Campo: ' + fmtN(ing.campo),
                'Access L:' + fmtN(ing.access_lab) + ' C:' + fmtN(ing.access_campo),
                'AppSheet L:' + fmtN(ing.appsheet_lab) + ' C:' + fmtN(ing.appsheet_campo)
            ]);
            html += statCard('Proformas generadas', fmtN(pg.total), [
                'Access: ' + fmtN(pg.access) + ' &middot; AppSheet: ' + fmtN(pg.appsheet)
            ]);
            html += statCard('Proformas aceptadas', fmtN(pa.total) + ' / ' + fmtN(pg.total), [
                'Access: ' + fmtN(pa.access) + ' &middot; AppSheet: ' + fmtN(pa.appsheet),
                pctAcept + '% de efectividad'
            ], '#15803d', pctAcept, '#15803d');
            html += statCard('Proformas gestionadas ' + esc(pgest.target_year || ''), 'Pend: ' + fmtN(pgest.pendientes) + ' / ' + fmtN(pgest.generadas_anual), [
                'Access: ' + fmtN(pgest.access) + ' &middot; AppSheet: ' + fmtN(pgest.appsheet),
                (pgest.pct || 0) + '% gestionado (Falta: ' + pctFaltaGestion + '%)'
            ], '#0f4bb4', pgest.pct, '#0f4bb4');
            html += statCard('Eficiencia aprobaci&oacute;n ' + esc(pef.target_year || ''), 'Rech: ' + fmtN(pef.rechazadas) + ' / ' + fmtN(pef.generadas_anual), [
                'Access: ' + fmtN(pef.access) + ' &middot; AppSheet: ' + fmtN(pef.appsheet),
                (pef.pct || 0) + '% eficiencia (Rechazo: ' + pctRechazo + '%)'
            ], '#b91c1c', pef.pct, '#b91c1c');
            html += '</div>';
            return html;
        }

        function renderFacturacion(fc) {
            if (!fc) return '';
            const cv = fc.credito_vencido || {};
            const cp = fc.contado_sin_pago || {};
            const fh = fc.facturados_hoy || {};
            const ph = fc.pagados_hoy || {};
            const ef = fc.eficiencia_facturacion || {};
            const ec = fc.eficiencia_cobro || {};

            let html = '<div class="seccion-titulo" style="color:#7c3aed;"><i class="fas fa-file-invoice-dollar"></i> 2. Facturaci&oacute;n y cobranzas</div>';
            html += '<div class="stat-cards">';
            html += statCard('Cr&eacute;dito vencido', fmtN(cv.total), [
                '(' + fmtN(cv.total) + ' OTs y ' + fmtN(cv.items_total) + ' Equipos)',
                'Access: ' + fmtN(cv.access) + ' - AppSheet: ' + fmtN(cv.appsheet)
            ], '#b91c1c');
            html += statCard('Contado sin pago', fmtN(cp.total), [
                '(' + fmtN(cp.total) + ' OTs y ' + fmtN(cp.items_total) + ' Equipos)',
                'Access: ' + fmtN(cp.access) + ' - AppSheet: ' + fmtN(cp.appsheet)
            ], '#b45309');
            html += statCard('Facturados hoy', fmtN(fh.items_total), [
                '(' + fmtN(fh.total) + ' OTs y ' + fmtN(fh.items_total) + ' Equipos)',
                'Access: ' + fmtN(fh.items_access) + ' - AppSheet: ' + fmtN(fh.items_appsheet)
            ], '#1d4ed8');
            html += statCard('Pagados hoy', fmtN(ph.items_total), [
                '(' + fmtN(ph.total) + ' OTs y ' + fmtN(ph.items_total) + ' Equipos)',
                'Access: ' + fmtN(ph.items_access) + ' - AppSheet: ' + fmtN(ph.items_appsheet)
            ], '#059669');
            html += '</div>';

            html += '<div class="stat-cards" style="margin-top:10px;">';
            html += statCard('Eficiencia de facturaci&oacute;n', (ef.porcentaje || 0) + '%', [
                fmtN(ef.facturadas) + ' / ' + fmtN(ef.aceptadas) + ' proformas'
            ], null, ef.porcentaje, '#8b5cf6');
            html += statCard('Eficiencia de cobro (pagos)', (ec.porcentaje || 0) + '%', [
                fmtN(ec.pagadas) + ' / ' + fmtN(ec.aceptadas) + ' pagadas'
            ], null, ec.porcentaje, '#10b981');
            html += '</div>';
            html += '<p class="nota">Nota: el denominador es el total de proformas aceptadas del mes actual.</p>';
            return html;
        }

        function renderCertificados(env) {
            if (!env) return '';
            const c = env.contado || {};
            const r = env.credito || {};
            const cTotal = (c.enviados_hoy || 0) + (c.listo_certs || 0);
            const cPct = cTotal > 0 ? Math.round((c.enviados_hoy / cTotal) * 100) : 100;
            const rTotal = (r.enviados_hoy || 0) + (r.listo_certs || 0);
            const rPct = rTotal > 0 ? Math.round((r.enviados_hoy / rTotal) * 100) : 100;

            let html = '<div class="seccion-titulo" style="color:#10b981;"><i class="fas fa-money-bill-wave"></i> 3.1 Env&iacute;o de certificados al contado</div>';
            html += '<div class="stat-cards">';
            html += statCard('Enviados hoy (contado)', fmtN(c.enviados_hoy) + ' certificados', []);
            html += statCard('Listos para enviar (contado)', 'OTs: ' + fmtN(c.listo_ots) + ' | Cert: ' + fmtN(c.listo_certs), []);
            html += statCard('Eficiencia env&iacute;o (contado)', cPct + '%', [
                fmtN(c.enviados_hoy) + ' cert. enviados vs ' + fmtN(c.listo_certs) + ' pendientes'
            ], null, cPct, '#10b981');
            html += '</div>';

            html += '<div class="seccion-titulo" style="color:#3b82f6;"><i class="fas fa-credit-card"></i> 3.2 Env&iacute;o de certificados a cr&eacute;dito</div>';
            html += '<div class="stat-cards">';
            html += statCard('Enviados hoy (cr&eacute;dito)', fmtN(r.enviados_hoy) + ' certificados', []);
            html += statCard('Listos para enviar (cr&eacute;dito)', 'OTs: ' + fmtN(r.listo_ots) + ' | Cert: ' + fmtN(r.listo_certs), []);
            html += statCard('Eficiencia env&iacute;o (cr&eacute;dito)', rPct + '%', [
                fmtN(r.enviados_hoy) + ' cert. enviados vs ' + fmtN(r.listo_certs) + ' pendientes'
            ], null, rPct, '#3b82f6');
            html += '</div>';
            return html;
        }

        function renderProduccionMetrologo(pm) {
            if (!pm) return '';
            let html = '<div class="seccion-titulo" style="color:#0f4bb4;"><i class="fas fa-industry"></i> 4. Producci&oacute;n y carga por laboratorio</div>';

            const buildProdTable = function (titulo, bloque, color) {
                if (!bloque || !bloque.rows || bloque.rows.length === 0) return '';
                let h = '<p class="subseccion">' + titulo + '</p>';
                const maxTotal = Math.max.apply(null, bloque.rows.map(function (p) { return p.total || 0; }));
                const rows = bloque.rows.map(function (p) {
                    return { cells: [esc(p.metrologo), fmtN(p.calibraciones), fmtN(p.certificaciones), celdaTotal(p.total, maxTotal, color)] };
                });
                const totCal = bloque.rows.reduce(function (s, p) { return s + (p.calibraciones || 0); }, 0);
                const totCert = bloque.rows.reduce(function (s, p) { return s + (p.certificaciones || 0); }, 0);
                const totAll = bloque.rows.reduce(function (s, p) { return s + (p.total || 0); }, 0);
                rows.push({ _cls: 'total', cells: ['TOTAL', fmtN(totCal), fmtN(totCert), fmtN(totAll)] });
                h += tabla(['Metr&oacute;logo', 'Cal.', 'Cert.', 'Total'], rows, color);
                return h;
            };

            html += buildProdTable('<i class="fas fa-flask"></i> Laboratorio &mdash; ' + esc(pm.laboratorio && pm.laboratorio.fecha_label), pm.laboratorio, '#0f766e');
            html += buildProdTable('<i class="fas fa-route"></i> Campo &mdash; ' + esc(pm.campo && pm.campo.rango_label), pm.campo, '#0f766e');
            return html;
        }

        function renderResumenComercial(rc) {
            if (!rc || !rc.rows || rc.rows.length === 0) return '';
            let html = '<p class="subseccion"><i class="fas fa-users"></i> Resumen de producci&oacute;n comercial &mdash; ' + esc(rc.fecha_label) + '</p>';
            const maxAceptMes = Math.max.apply(null, rc.rows.map(function (r) { return r.aceptadas_mes || 0; }));
            const rows = rc.rows.map(function (r) {
                return {
                    _cls: (rc.top_ejecutivo_mes && r.ejecutivo === rc.top_ejecutivo_mes) ? 'destacada' : '',
                    cells: [esc(r.ejecutivo), fmtN(r.aceptadas), fmtN(r.eq_aceptados), fmtN(r.rechazadas), fmtN(r.eq_rechazados), fmtN(r.seguimientos), celdaTotal(r.aceptadas_mes, maxAceptMes, '#15803d')]
                };
            });
            const sum = function (k) { return rc.rows.reduce(function (s, r) { return s + (r[k] || 0); }, 0); };
            rows.push({ _cls: 'total', cells: ['TOTAL', fmtN(sum('aceptadas')), fmtN(sum('eq_aceptados')), fmtN(sum('rechazadas')), fmtN(sum('eq_rechazados')), fmtN(sum('seguimientos')), fmtN(sum('aceptadas_mes'))] });
            html += tabla(['Ejecutivo', 'Aceptadas<br>(D&iacute;a)', 'Eq.<br>Aceptados', 'Rechazadas<br>(D&iacute;a)', 'Eq.<br>Rechazados', 'Seguim.<br>(D&iacute;a)', 'Aceptadas<br>(Mes)'], rows, '#1e3a5f');
            return html;
        }

        function renderProduccionCarga(pc) {
            if (!pc || !pc.rows || pc.rows.length === 0) return '';
            let html = '<div class="banner-info"><span>Ingreso total del d&iacute;a (Access + AppSheet):</span><b>' + fmtN(pc.ingreso_total) + ' equipos</b></div>';
            const rows = pc.rows.map(function (r) {
                return { cells: [esc(r.laboratorio), fmtN(r.ingreso), fmtN(r.calibrado), fmtN(r.restante), r.pct_despeje + '%', r.pct_avance + '%'] };
            });
            const sum = function (k) { return pc.rows.reduce(function (s, r) { return s + (r[k] || 0); }, 0); };
            const totCarga = sum('calibrado') + sum('restante');
            const totCargaInicial = Math.max(0, sum('restante') + sum('calibrado') - sum('ingreso'));
            const totEfici = totCargaInicial > 0 ? Math.round((sum('calibrado') / totCargaInicial) * 100) : (sum('calibrado') > 0 ? 100 : 0);
            const totAvance = totCarga > 0 ? Math.round((sum('calibrado') / totCarga) * 100) : 0;
            rows.push({ _cls: 'total', cells: ['TOTALES CONSOLIDADOS', fmtN(sum('ingreso')), fmtN(sum('calibrado')), fmtN(sum('restante')), totEfici + '%', totAvance + '%'] });
            html += tabla(['Laboratorio / Magnitud', 'Ingreso<br>Hoy', 'Calibrado<br>Hoy', 'Carga<br>Restante', '%<br>Despeje', '%<br>Avance'], rows, '#0f766e');
            html += '<p class="nota">* % Despeje: eficiencia evacuando la mora antigua &mdash; Calibrado Hoy / (Restante + Calibrado - Ingreso).</p>';
            html += '<p class="nota">* % Avance: progreso frente a la carga acumulada total &mdash; Calibrado Hoy / (Restante + Calibrado).</p>';
            return html;
        }

        function renderAnulaciones(an) {
            if (!an) return '';
            let html = '<div class="seccion-titulo" style="color:#dc2626;"><i class="fas fa-ban"></i> 5. Anulaciones (' + fmtN(an.total) + ')</div>';
            if (!an.rows || an.rows.length === 0) {
                html += '<p class="nota">Sin anulaciones registradas.</p>';
                return html;
            }
            const rows = an.rows.map(function (r) {
                return { cells: [esc(r.empresa), esc(r.ot), esc(r.item), esc(r.equipo), esc(r.metrologo), esc(r.fecha), esc(r.motivo), esc(r.ejecutiva)] };
            });
            html += tabla(['Empresa', 'OT', 'Item', 'Equipo', 'Metr&oacute;logo', 'Fecha', 'Motivo', 'Ejecutiva'], rows, '#991b1b');
            return html;
        }

        function renderEquiposPrevistos(ep) {
            if (!ep || !ep.rows || ep.rows.length === 0) return '';
            let html = '<div class="seccion-titulo" style="color:#312e81;"><i class="fas fa-dolly"></i> 7. Equipos previstos de ingreso</div>';
            html += '<p class="nota" style="margin-bottom:10px;">Proformas aceptadas con instrumento sin Orden de Trabajo. Ordenado de mayor a menor por laboratorio.</p>';
            html += '<div class="summary-cards">';
            html += '<div class="mini"><div class="l">Equipos previstos</div><div class="v">' + fmtN(ep.total) + '</div></div>';
            html += '<div class="mini"><div class="l">Laboratorios</div><div class="v">' + fmtN(ep.laboratorios) + '</div></div>';
            html += '<div class="mini"><div class="l">Proformas / grupos</div><div class="v">' + fmtN(ep.grupos) + '</div></div>';
            html += '</div>';

            // --- Resumen totalizado por laboratorio (vista rapida) ---
            html += '<p class="subseccion"><i class="fas fa-list-ol"></i> Resumen por laboratorio</p>';
            const maxTotal = Math.max.apply(null, ep.rows.map(function (r) { return r.total || 0; }));
            const resumenRows = ep.rows.map(function (r) {
                return { cells: [esc(r.laboratorio), celdaTotal(r.total, maxTotal, '#4338ca')] };
            });
            resumenRows.push({ _cls: 'total', cells: ['TOTAL GENERAL', fmtN(ep.total)] });
            html += tabla(['Laboratorio', 'Total de equipos'], resumenRows, '#312e81');

            // --- Detalle por laboratorio: lista ordenada (equipo | cantidad), no texto corrido ---
            html += '<p class="subseccion"><i class="fas fa-list"></i> Detalle por laboratorio</p>';
            html += '<div class="detalle-labs-grid">';
            ep.rows.forEach(function (r) {
                html += '<div class="detalle-lab-card">';
                html += '<div class="detalle-lab-header"><span>' + esc(r.laboratorio) + '</span><span class="total">' + fmtN(r.total) + '</span></div>';
                if (r.items && r.items.length > 0) {
                    html += '<ul class="detalle-lab-lista">';
                    r.items.forEach(function (it) {
                        html += '<li><span class="nombre">' + esc(it.nombre) + '</span><span class="cant">' + fmtN(it.cantidad) + '</span></li>';
                    });
                    if (r.otros_count) {
                        html += '<li class="otros"><span class="nombre">+ ' + fmtN(r.otros_count) + ' equipo(s) m&aacute;s</span><span class="cant">' + fmtN(r.otros_total) + '</span></li>';
                    }
                    html += '</ul>';
                } else if (r.equipos) {
                    // Compatibilidad con snapshots generados antes de este formato.
                    html += '<p class="nota" style="margin:0;">' + esc(r.equipos) + '</p>';
                }
                html += '</div>';
            });
            html += '</div>';
            return html;
        }

        function renderProgramacionesPendientes(pp) {
            if (!pp) return '';
            let html = '<p class="subseccion"><i class="fas fa-map-marked-alt"></i> Programaciones de Campo Pendientes (' + fmtN(pp.total) + ')</p>';
            if (!pp.rows || pp.rows.length === 0) {
                html += '<p class="nota" style="color:#15803d; font-weight:700; font-style:normal;">Sin programaciones pendientes &mdash; todo el backlog de Campo est&aacute; programado.</p>';
                return html;
            }
            const rows = pp.rows.map(function (r) {
                const dias = Number(r.dias) || 0;
                const color = dias > 15 ? '#b91c1c' : (dias > 7 ? '#b45309' : '#15803d');
                const diasCell = '<span style="color:' + color + '; font-weight:700;">' + dias + 'd</span>';
                return { cells: [esc(r.ot), esc(r.empresa), fmtN(r.equipos), diasCell] };
            });
            html += tabla(['OT', 'Empresa', 'Equipos', 'D&iacute;as'], rows, '#b45309');
            return html;
        }

        function render(data) {
            const app = document.getElementById('app');
            if (!data) {
                app.innerHTML = '<div class="estado-vacio">No se encontr&oacute; informaci&oacute;n para este reporte.</div>';
                return;
            }

            const ytd = data.crecimiento_ytd_info || {};
            const mensual = data.tendencia_mensual || {};
            const semanal = data.tendencia_semanal || {};
            const ytdClase = claseTendencia(data.crecimiento_ytd);
            const mesClase = claseTendencia(mensual.variacion_porcentual);
            const semClase = claseTendencia(semanal.variacion_porcentual);

            let html = `
                <header class="encabezado">
                    <h1>Reporte Ejecutivo de KPIs</h1>
                    <p class="subtitulo">Metrolog&iacute;a &amp; Servicios &middot; Generado el ${esc(data.generation_date || '')}</p>
                    <p class="consultado">Datos consultados: ${esc(data.consulted_date || '')}</p>
                </header>
            `;

            html += renderResumenEjecutivo(data);

            html += `
                <div class="kpi-grid">
                    <div class="kpi-card">
                        <p class="titulo">Acumulado anual (${esc(data.report_year)} vs ${esc(data.report_year - 1)})</p>
                        <p class="valor ${ytdClase}">${formatPct(data.crecimiento_ytd)}</p>
                        <p class="detalle">${esc(ytd.anio_actual || '')}: ${fmtN(ytd.total_actual)} equipos</p>
                        <p class="detalle">${esc(ytd.anio_anterior || '')}: ${fmtN(ytd.total_anterior)} equipos</p>
                    </div>
                    <div class="kpi-card">
                        <p class="titulo">Mes actual (corte ${esc(mensual.dia_corte || '')} ${esc(mensual.mes || '')})</p>
                        <p class="valor ${mesClase}">${formatPct(mensual.variacion_porcentual)}</p>
                        <p class="detalle">${esc(mensual.mes || '')} ${esc(data.report_year)}: ${fmtN(mensual.produccion_actual)} equipos</p>
                        <p class="detalle">${esc(mensual.mes || '')} ${esc(data.report_year - 1)}: ${fmtN(mensual.produccion_anterior)} equipos</p>
                    </div>
                    <div class="kpi-card">
                        <p class="titulo">Semana actual (semana ${esc(semanal.semana || '')})</p>
                        <p class="valor ${semClase}">${formatPct(semanal.variacion_porcentual)}</p>
                        <p class="detalle">Sem ${esc(semanal.semana || '')} ${esc(data.report_year)}: ${fmtN(semanal.produccion_actual)} equipos</p>
                        <p class="detalle">Sem ${esc(semanal.semana || '')} ${esc(data.report_year - 1)}: ${fmtN(semanal.produccion_anterior)} equipos</p>
                    </div>
                </div>
            `;

            const produccionHtml = renderProduccionMetrologo(data.produccion_metrologo)
                + renderProgramacionesPendientes(data.programaciones_pendientes)
                + renderResumenComercial(data.resumen_comercial)
                + renderProduccionCarga(data.produccion_carga_laboratorio);

            const sections = [
                { id: 'sec-comercial', icon: 'fa-briefcase', label: 'Comercial', html: renderGestionComercial(data.gestion_comercial) },
                { id: 'sec-facturacion', icon: 'fa-file-invoice-dollar', label: 'Facturaci&oacute;n', html: renderFacturacion(data.facturacion_cobranzas) },
                { id: 'sec-certificados', icon: 'fa-certificate', label: 'Certificados', html: renderCertificados(data.envios_certificados) },
                { id: 'sec-produccion', icon: 'fa-industry', label: 'Producci&oacute;n', html: produccionHtml },
                { id: 'sec-anulaciones', icon: 'fa-ban', label: 'Anulaciones', html: renderAnulaciones(data.anulaciones) },
                { id: 'sec-previstos', icon: 'fa-dolly', label: 'Previstos', html: renderEquiposPrevistos(data.equipos_previstos) }
            ].filter(function (s) { return s.html && s.html.trim() !== ''; });

            if (sections.length > 0) {
                html += '<nav class="nav-secciones">' + sections.map(function (s) {
                    return '<a href="#' + s.id + '"><i class="fas ' + s.icon + '"></i> ' + s.label + '</a>';
                }).join('') + '</nav>';
            }

            sections.forEach(function (s) {
                html += '<section id="' + s.id + '">' + s.html + '</section>';
            });

            html += `
                <footer class="pie">
                    <span>Metrolog&iacute;a &amp; Servicios</span>
                    <span>Reporte generado el ${esc(data.generation_date || '')}</span>
                </footer>
            `;

            app.innerHTML = html;
        }

        async function cargarYRenderizar() {
            const app = document.getElementById('app');
            const params = new URLSearchParams(window.location.search);
            const token = params.get('token');

            if (!token) {
                app.innerHTML = '<div class="estado-vacio">Falta el identificador del reporte en el link.</div>';
                return;
            }

            // Validacion basica del formato esperado del token (mismo patron que
            // genera secrets.token_urlsafe en el backend, o el identificador
            // legible tipo Reporte_KPIs_YYYY-MM-DD) -- solo para evitar pedir una
            // URL con caracteres raros, no es una medida de seguridad (los datos
            // igual son publicos de por si en el bucket).
            if (!/^[A-Za-z0-9_-]{16,64}$/.test(token)) {
                app.innerHTML = '<div class="estado-vacio">Link de reporte inv&aacute;lido.</div>';
                return;
            }

            const dataUrl = `${SUPABASE_URL}/storage/v1/object/public/${SUPABASE_BUCKET}/${encodeURIComponent(token)}.json`;

            try {
                let resp = await fetch(dataUrl);
                if (!resp.ok) {
                    const respAnterior = await fetch(dataUrl.replace(SUPABASE_URL, SUPABASE_URL_ANTERIOR)).catch(() => null);
                    if (respAnterior && respAnterior.ok) resp = respAnterior;
                }
                if (!resp.ok) {
                    app.innerHTML = resp.status === 404
                        ? '<div class="estado-vacio">Este reporte no existe o fue eliminado.</div>'
                        : '<div class="estado-vacio">No se pudo cargar el reporte (error de red).</div>';
                    return;
                }
                const snapshot = await resp.json();
                render(snapshot.data || snapshot);
            } catch (e) {
                console.error(e);
                app.innerHTML = '<div class="estado-vacio">Ocurri&oacute; un error cargando el reporte. Verifica tu conexi&oacute;n a internet.</div>';
            }
        }

        cargarYRenderizar();
    </script>
</body>
</html>
