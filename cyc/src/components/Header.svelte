<style>
  .Header {
    background-color: white;
    position: fixed;
    width: 100%;
  }
  .Header-container {
    display: grid;
    grid-template-columns: minmax(auto, 936px);
    justify-content: center;
    background-color: rgb(242, 242, 242);
    border-bottom: 1px solid rgba(38, 38, 38, 0.4);
  }
  .Header-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0.5em;
  }
  .Header-nav :hover{
    color: #01691b;
  }
  .Header ul {
    list-style: none;
  }
  .Header li {
    display: inline-block;
    margin: 0 0 0 1em;
  }
  .Header i {
    font-size: 16px;
    color: rgba(38, 38, 38, 0.7);
    cursor: pointer;
  }

  h1 {
    padding: 0;
    margin: 0;
    font-size: 28px;
    color: black;
    font-family: "Pacifico", cursive;
    cursor: pointer;
    position: relative;
    background: #fff;
    mix-blend-mode: multiply;
    display: inline-block;
  }

  h1:before {
    content: "";
    display: block;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at top left, #33f033, #01691b);
    mix-blend-mode: screen;
    position: absolute;
    top: 0;
    left: 0;
  }
</style>

<div class="Header">
    <div class="Header-container">
        <div class="Header-content">
            <div class="Header-logo">
                <h1>CyC</h1>
            </div>
            <div class="Header-nav">
                <ul>
                    <li>
                      <i>Inicio</i>
                    </li>
                    <li>
                      <i>Sobre nosotros</i>
                    </li>
                    <li>
                      <i>Trabajos</i>
                    </li>
                    <li>
                      <i>Contacto</i>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</div>