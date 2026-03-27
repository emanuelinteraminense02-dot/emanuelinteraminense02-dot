<style>
  /* Animação de entrada (FadeIn) */
  @keyframes fadeIn {
    0% { opacity: 0; transform: translateY(10px); }
    100% { opacity: 1; transform: translateY(0); }
  }

  /* Animação de pulso para o status de 'Open to Work' */
  @keyframes pulse {
    0% { box-shadow: 0 0 0 0 rgba(76, 175, 80, 0.4); }
    70% { box-shadow: 0 0 0 10px rgba(76, 175, 80, 0); }
    100% { box-shadow: 0 0 0 0 rgba(76, 175, 80, 0); }
  }

  /* Aplicação das animações nas tags HTML */
  #main-container {
    animation: fadeIn 1s ease-out;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  }

  .skill-badge:hover {
    transform: translateY(-3px);
    transition: transform 0.2s ease;
  }
</style>

<div id="main-container" style="color: #c9d1d9; border-radius: 12px; padding: 1px;">

  <div align="center" style="margin-top: 20px;">
    <img src="https://capsule-render.vercel.app/api?type=distort&color=121212&height=180&section=header&text=Emanuel%20Interaminense&fontSize=65&animation=fadeIn&fontAlignY=35&fontAlign=center&stroke=007ACC&strokeWidth=1" alt="Header Banner" width="100%"/>
    
    <div style="margin-top: -30px; margin-bottom: 20px;">
      <span style="background-color: #1a1a1a; color: #4CAF50; border: 1px solid #4CAF50; padding: 6px 14px; border-radius: 20px; font-size: 13px; font-weight: 600; display: inline-flex; align-items: center; animation: pulse 2s infinite; text-transform: uppercase; letter-spacing: 1px;">
        <span style="color: #4CAF50; margin-right: 6px;">●</span> Disponível para Oportunidades
      </span>
    </div>

    <h2 style="border-bottom: none; color: #007ACC; font-weight: 700; margin-top: 0;">Desenvolvedor de Sistemas & Especialista em IA</h2>
    
    <p style="font-size: 16px; color: #8b949e; max-width: 600px; margin-top: -10px;">
      Estudante Técnico no <b>Senac</b>. Focado na intersecção entre desenvolvimento de software de alta performance e Inteligência Artificial Aplicada.
    </p>
  </div>

  <hr style="border: 1px solid #21262d; margin: 30px 0;">

  <div align="center">
    <h3 style="border-bottom: none; color: #c9d1d9; margin-bottom: 20px;">💻 Stack Tecnológica Homologada</h3>
  </div>

  <table align="center" style="border-collapse: collapse; border: none; width: 100%; max-width: 800px; background-color: transparent;">
    <tr style="background-color: transparent; border: none;">
      <td width="33%" valign="top" style="border: none; padding: 10px;">
        <div style="background-color: #161b22; border: 1px solid #30363d; border-radius: 8px; padding: 20px; height: 200px; text-align: center; display: flex; flex-direction: column; align-items: center; justify-content: start;">
          <img src="https://img.icons8.com/fluency/48/000000/code.png" alt="Front Icon" width="30"/>
          <strong style="color: #007ACC; display: block; margin: 10px 0;">Front-end Engine</strong>
          <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 6px;">
            <img class="skill-badge" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" height="22"/>
            <img class="skill-badge" src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" height="22"/>
            <img class="skill-badge" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="22"/>
          </div>
        </div>
      </td>
      <td width="33%" valign="top" style="border: none; padding: 10px;">
        <div style="background-color: #161b22; border: 1px solid #30363d; border-radius: 8px; padding: 20px; height: 200px; text-align: center; display: flex; flex-direction: column; align-items: center; justify-content: start;">
          <img src="https://img.icons8.com/fluency/48/000000/database-restore.png" alt="Data Icon" width="30"/>
          <strong style="color: #007ACC; display: block; margin: 10px 0;">Data & Core</strong>
          <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 6px;">
            <img class="skill-badge" src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" height="22"/>
            <img class="skill-badge" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" height="22"/>
            <img class="skill-badge" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" height="22"/>
          </div>
        </div>
      </td>
      <td width="33%" valign="top" style="border: none; padding: 10px;">
        <div style="background-color: #161b22; border: 1px solid #30363d; border-radius: 8px; padding: 20px; height: 200px; text-align: center; display: flex; flex-direction: column; align-items: center; justify-content: start;">
          <img src="https://img.icons8.com/fluency/48/000000/artificial-intelligence.png" alt="AI Icon" width="30"/>
          <strong style="color: #007ACC; display: block; margin: 10px 0;">AI & Vision</strong>
          <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 6px;">
            <img class="skill-badge" src="https://img.shields.io/badge/Computer_Vision-5C3EE8?style=flat-square" height="22"/>
            <img class="skill-badge" src="https://img.shields.io/badge/OpenCV-FFFFFF?style=flat-square&logo=opencv&logoColor=black" height="22"/>
            <img class="skill-badge" src="https://img.shields.io/badge/Core_AI-000000?style=flat-square" height="22"/>
          </div>
        </div>
      </td>
    </tr>
  </table>

  <hr style="border: 1px solid #21262d; margin: 30px 0;">

  <div align="center">
    <h3 style="border-bottom: none; color: #c9d1d9;">📂 Projetos Homologados</h3>
  </div>

  <div style="max-width: 800px; margin: 0 auto;">
    <blockquote style="border-left: 4px solid #007ACC; background-color: #161b22; padding: 15px; border-radius: 6px; margin-bottom: 10px; color: #8b949e;">
      <strong style="color: #c9d1d9; font-size: 16px;">Admin Dashboard Enterprise</strong><br>
      Painel administrativo focado em telemetria de dados e performance corporativa.<br>
      <code style="color: #79c0ff; font-size: 12px; background: none; padding: 0;">Stack: JavaScript, Node.js, SQL.</code>
    </blockquote>
    <blockquote style="border-left: 4px solid #007ACC; background-color: #161b22; padding: 15px; border-radius: 6px; color: #8b949e;">
      <strong style="color: #c9d1d9; font-size: 16px;">Edge AI Traffic Optimizer</strong><br>
      Pesquisa aplicada em Visão Computacional para monitoramento inteligente de vias urbanas.<br>
      <code style="color: #79c0ff; font-size: 12px; background: none; padding: 0;">Foco: Python, Computer Vision, Automação.</code>
    </blockquote>
  </div>

  <hr style="border: 1px solid #21262d; margin: 30px 0;">

  <div align="center" style="margin-bottom: 30px;">
    <h3 style="border-bottom: none; color: #c9d1d9; margin-bottom: 15px;">📫 Communication Channels</h3>
    <a href="https://www.linkedin.com/in/emanuel-interaminense-a59a423ba/" target="_blank" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;&nbsp;
    <a href="mailto:emanuel.interaminense1@gmail.com" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </div>

  <div align="center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=121212&height=90&section=footer" alt="Footer Wave" width="100%"/>
    <p style="color: #30363d; font-size: 11px; margin-top: -30px;">Protocolo: IMPECCABLE_v1.0 // EmanTech Solutions</p>
  </div>

</div>
