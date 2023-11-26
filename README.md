# UniAmérica | Atividade prática - Módulo 10

![Logo faculdade](https://no.descomplica.com.br/hubfs/Logo-Faculdade-Preto-Verde-May-10-2022-10-15-22-32-PM.png)

## Diff do que eu mudei:

<details>
  <summary> <samp>&#9776; Visualizar</samp></summary>

  ```diff
diff --git a/modulo10/template-materialui/README.md b/modulo10/template-materialui/README.md
index ff33d78..0c28b97 100644
--- a/modulo10/template-materialui/README.md
+++ b/modulo10/template-materialui/README.md
@@ -1,15 +1,22 @@
-# Aplicação React de Gerenciamento de Projetos e Tarefas
+# UniAmérica | Atividade prática - Módulo 10
+
+![Logo faculdade](https://no.descomplica.com.br/hubfs/Logo-Faculdade-Preto-Verde-May-10-2022-10-15-22-32-PM.png)
+
+## Diff do que eu mudei:
+
+<details>
+  <summary> <samp>&#9776; Visualizar</samp></summary>
+  ```diff
+    <diff>
+  ```
+</details>
+
+## Aplicação React de Gerenciamento de Projetos e Tarefas
 
 Projeto criado com as bibliotecas React JS e Material UI.
 
-## Passo-a-passo para execução
+### Passo-a-passo para execução
 
 1. Clonar o repositório
 2. Localmente, entrar na pasta do projeto e instalar as dependências:
-   `
-   npm install
-   `
+   `npm install`
 3. Executar a aplicação:
-   `
-   npm start
-   `
\ No newline at end of file
+   `npm start`
diff --git a/modulo10/template-materialui/src/App.test.js b/modulo10/template-materialui/src/App.test.js
index 1f03afe..9382b9a 100644
--- a/modulo10/template-materialui/src/App.test.js
+++ b/modulo10/template-materialui/src/App.test.js
@@ -1,7 +1,7 @@
-import { render, screen } from '@testing-library/react';
-import App from './App';
+import { render, screen } from "@testing-library/react";
+import App from "./App";
 
-test('renders learn react link', () => {
+test("renders learn react link", () => {
   render(<App />);
   const linkElement = screen.getByText(/learn react/i);
   expect(linkElement).toBeInTheDocument();
diff --git a/modulo10/template-materialui/src/components/header.js b/modulo10/template-materialui/src/components/header.js
index 2d0a879..214a112 100644
--- a/modulo10/template-materialui/src/components/header.js
+++ b/modulo10/template-materialui/src/components/header.js
@@ -1,35 +1,35 @@
-import * as React from 'react';
-import AppBar from '@mui/material/AppBar';
-import Box from '@mui/material/Box';
-import Toolbar from '@mui/material/Toolbar';
-import Typography from '@mui/material/Typography';
-import Button from '@mui/material/Button';
-import IconButton from '@mui/material/IconButton';
+import * as React from "react";
+import AppBar from "@mui/material/AppBar";
+import Box from "@mui/material/Box";
+import Toolbar from "@mui/material/Toolbar";
+import Typography from "@mui/material/Typography";
+import Button from "@mui/material/Button";
+import IconButton from "@mui/material/IconButton";
 //import MenuIcon from '@mui/icons-material/Menu';
- 
+
 function Header() {
-    return (
-        <Box sx={{ flexGrow: 1 }}>
-        <AppBar position="static">
-          <Toolbar>
-            <IconButton
-              size="large"
-              edge="start"
-              color="inherit"
-              aria-label="menu"
-              sx={{ mr: 2 }}
-            >
-              {/*  
+  return (
+    <Box sx={{ flexGrow: 1 }}>
+      <AppBar position="static">
+        <Toolbar>
+          <IconButton
+            size="large"
+            edge="start"
+            color="inherit"
+            aria-label="menu"
+            sx={{ mr: 2 }}
+          >
+            {/*  
               <MenuIcon />
               */}
-            </IconButton>
-            <Typography variant="h6" component="div" sx={{ flexGrow: 1 }}>
-              Gerenciamento de Projetos
-            </Typography>
-          </Toolbar>
-        </AppBar>
-      </Box>
-    );
+          </IconButton>
+          <Typography variant="h6" component="div" sx={{ flexGrow: 1 }}>
+            Gerenciamento de Projetos
+          </Typography>
+        </Toolbar>
+      </AppBar>
+    </Box>
+  );
 }
- 
-export default Header;
\ No newline at end of file
+
+export default Header;
diff --git a/modulo10/template-materialui/src/index.css b/modulo10/template-materialui/src/index.css
index ec2585e..4a1df4d 100644
--- a/modulo10/template-materialui/src/index.css
+++ b/modulo10/template-materialui/src/index.css
@@ -1,13 +1,13 @@
 body {
   margin: 0;
-  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
-    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
+  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen",
+    "Ubuntu", "Cantarell", "Fira Sans", "Droid Sans", "Helvetica Neue",
     sans-serif;
   -webkit-font-smoothing: antialiased;
   -moz-osx-font-smoothing: grayscale;
 }
 
 code {
-  font-family: source-code-pro, Menlo, Monaco, Consolas, 'Courier New',
+  font-family: source-code-pro, Menlo, Monaco, Consolas, "Courier New",
     monospace;
 }
diff --git a/modulo10/template-materialui/src/index.js b/modulo10/template-materialui/src/index.js
index d563c0f..902eb7c 100644
--- a/modulo10/template-materialui/src/index.js
+++ b/modulo10/template-materialui/src/index.js
@@ -1,14 +1,14 @@
-import React from 'react';
-import ReactDOM from 'react-dom/client';
-import './index.css';
-import App from './App';
-import reportWebVitals from './reportWebVitals';
+import React from "react";
+import ReactDOM from "react-dom/client";
+import "./index.css";
+import App from "./App";
+import reportWebVitals from "./reportWebVitals";
 
-const root = ReactDOM.createRoot(document.getElementById('root'));
+const root = ReactDOM.createRoot(document.getElementById("root"));
 root.render(
   <React.StrictMode>
     <App />
-  </React.StrictMode>
+  </React.StrictMode>,
 );
 
 // If you want to start measuring performance in your app, pass a function
diff --git a/modulo10/template-materialui/src/pages/tarefa/CriarTarefa.jsx b/modulo10/template-materialui/src/pages/tarefa/CriarTarefa.jsx
index 0f528d9..10fcd62 100644
--- a/modulo10/template-materialui/src/pages/tarefa/CriarTarefa.jsx
+++ b/modulo10/template-materialui/src/pages/tarefa/CriarTarefa.jsx
@@ -1,29 +1,28 @@
-import React, {useState, useEffect} from 'react';
-import { FormControl, InputLabel, Input, FormHelperText } from '@mui/material';
-import MenuItem from '@mui/material/MenuItem';
-import Select from '@mui/material/Select';
-import Grid from '@mui/material/Grid';
-import Card from '@mui/material/Card';
-import CardHeader from '@mui/material/CardHeader';
-import CardContent from '@mui/material/CardContent';
-import CardActions from '@mui/material/CardActions';
-import Button from '@mui/material/Button';
+import React, { useState, useEffect } from "react";
+import { FormControl, InputLabel, Input, FormHelperText } from "@mui/material";
+import MenuItem from "@mui/material/MenuItem";
+import Select from "@mui/material/Select";
+import Grid from "@mui/material/Grid";
+import Card from "@mui/material/Card";
+import CardHeader from "@mui/material/CardHeader";
+import CardContent from "@mui/material/CardContent";
+import Button from "@mui/material/Button";
 
 //Declaração do componente CriarTarefa, recebendo como props, do Componente ListarTarefa, os states handClose, tarefas e setTarefas
-const CriarTarefa = ({handleClose, tarefas, setTarefas}) =>{
+const CriarTarefa = ({ handleClose, tarefas, setTarefas }) => {
   const [idTarefa, setIdTarefa] = useState();
-  const [tituloTarefa, setTituloTarefa] = useState('');
-  const [descricaoTarefa, setDescricaoTarefa] = useState('');
-  const [inicioTarefa, setInicioTarefa] = useState('');
-  const [fimTarefa, setFimTarefa] = useState('');
-  const [recursoTarefa, setRecursoTarefa] = useState('');
-  const [statusTarefa, setStatusTarefa] = useState('');
-  
+  const [tituloTarefa, setTituloTarefa] = useState("");
+  const [descricaoTarefa, setDescricaoTarefa] = useState("");
+  const [inicioTarefa, setInicioTarefa] = useState("");
+  const [fimTarefa, setFimTarefa] = useState("");
+  const [recursoTarefa, setRecursoTarefa] = useState("");
+  const [statusTarefa, setStatusTarefa] = useState("");
+
   useEffect(() => {
     //Abaixo uma variável é declarada para armazenar o id da tarefa, somando 1 ao maior id existente atualmente no state Tarefas
-    let proximoId = Math.max(...tarefas.map(tarefa => tarefa.idTarefa)) + 1;
+    let proximoId = Math.max(...tarefas.map((tarefa) => tarefa.idTarefa)) + 1;
     setIdTarefa(proximoId);
-  },[]);
+  }, []);
 
   const handleRecurso = (event) => {
     setRecursoTarefa(event.target.value);
@@ -36,73 +35,110 @@ const CriarTarefa = ({handleClose, tarefas, setTarefas}) =>{
   const handleSalvar = () => {
     //Para inspecionarmos nosso código, uma boa estratégia é utilizarmos o console.log.
     //  Com o console.log, podemos visualizar o seu conteúdo na aba Console, no inspecionador de elementos, na janela do navegador
-    console.log(`id: ${idTarefa} \n titulo: ${tituloTarefa} \n descrição: ${descricaoTarefa} \n inicio: ${inicioTarefa} \n fim: ${fimTarefa} \n recurso: ${recursoTarefa} \n status: ${statusTarefa}`);
+    console.log(
+      `id: ${idTarefa} \n titulo: ${tituloTarefa} \n descrição: ${descricaoTarefa} \n inicio: ${inicioTarefa} \n fim: ${fimTarefa} \n recurso: ${recursoTarefa} \n status: ${statusTarefa}`,
+    );
 
-    setTarefas(
-      [...tarefas, 
-        {
-          idTarefa,
-          tituloTarefa,
-          descricaoTarefa,
-          inicioTarefa,
-          fimTarefa,
-          recursoTarefa,
-          statusTarefa
-        }
-      ]);
+    setTarefas([
+      ...tarefas,
+      {
+        idTarefa,
+        tituloTarefa,
+        descricaoTarefa,
+        inicioTarefa,
+        fimTarefa,
+        recursoTarefa,
+        statusTarefa,
+      },
+    ]);
     //console.log(`Tarefas: ` + JSON.stringify(tarefas));
     handleClose();
   };
 
-  return(
+  return (
     <Grid container spacing={2}>
       <Card sx={style}>
-        <CardHeader
-          title="Tarefas"
-          subheader="Cadastro de Tarefas"
-        /> 
-        <CardContent sx={{
-          width: '95%',
-          maxWidth: '100%',
-        }}>
+        <CardHeader title="Tarefas" subheader="Cadastro de Tarefas" />
+        <CardContent
+          sx={{
+            width: "95%",
+            maxWidth: "100%",
+          }}
+        >
           <Grid item xs={12}>
             <FormControl fullWidth>
-              <Input id="tarefa_titulo" aria-describedby="tarefa_titulo_helper_text" value={tituloTarefa} onChange={e => { setTituloTarefa(e.target.value) }} />
-              <FormHelperText id="tarefa_titulo_helper_text">Título da Tarefa.</FormHelperText>
+              <Input
+                id="tarefa_titulo"
+                aria-describedby="tarefa_titulo_helper_text"
+                value={tituloTarefa}
+                onChange={(e) => {
+                  setTituloTarefa(e.target.value);
+                }}
+              />
+              <FormHelperText id="tarefa_titulo_helper_text">
+                Título da Tarefa.
+              </FormHelperText>
             </FormControl>
           </Grid>
-          <Grid item xs={12}>  
+          <Grid item xs={12}>
             <FormControl fullWidth>
-              <Input id="tarefa_descricao" aria-describedby="tarefa_descricao_helper_text" value={descricaoTarefa} onChange={e => { setDescricaoTarefa(e.target.value) }} />
-              <FormHelperText id="tarefa_descricao_helper_text">Descrição da Tarefa.</FormHelperText>
+              <Input
+                id="tarefa_descricao"
+                aria-describedby="tarefa_descricao_helper_text"
+                value={descricaoTarefa}
+                onChange={(e) => {
+                  setDescricaoTarefa(e.target.value);
+                }}
+              />
+              <FormHelperText id="tarefa_descricao_helper_text">
+                Descrição da Tarefa.
+              </FormHelperText>
             </FormControl>
           </Grid>
           <Grid container spacing={2} mt={1}>
-            <Grid item xs={3}>  
+            <Grid item xs={3}>
               <FormControl>
-                <Input id="tarefa_inicio" type="date" aria-describedby="tarefa_inicio_helper_text" value={inicioTarefa} onChange={e => { setInicioTarefa(e.target.value) }}
+                <Input
+                  id="tarefa_inicio"
+                  type="date"
+                  aria-describedby="tarefa_inicio_helper_text"
+                  value={inicioTarefa}
+                  onChange={(e) => {
+                    setInicioTarefa(e.target.value);
+                  }}
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                    paddingLeft:'13px'
-                  }} 
+                    paddingLeft: "13px",
+                  }}
                 />
-                <FormHelperText id="tarefa_inicio_helper_text">Início da Tarefa.</FormHelperText>
+                <FormHelperText id="tarefa_inicio_helper_text">
+                  Início da Tarefa.
+                </FormHelperText>
               </FormControl>
-            </Grid>  
-            <Grid item xs={3}>  
+            </Grid>
+            <Grid item xs={3}>
               <FormControl>
-                <Input id="tarefa_fim" type="date" aria-describedby="tarefa_fim_helper_text" value={fimTarefa} onChange={e => { setFimTarefa(e.target.value) }}
+                <Input
+                  id="tarefa_fim"
+                  type="date"
+                  aria-describedby="tarefa_fim_helper_text"
+                  value={fimTarefa}
+                  onChange={(e) => {
+                    setFimTarefa(e.target.value);
+                  }}
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                    paddingLeft:'13px'
-                  }} 
+                    paddingLeft: "13px",
+                  }}
                 />
-                <FormHelperText id="tarefa_fim_helper_text">Fim da Tarefa.</FormHelperText>
+                <FormHelperText id="tarefa_fim_helper_text">
+                  Fim da Tarefa.
+                </FormHelperText>
               </FormControl>
             </Grid>
-            <Grid item xs={3}>  
+            <Grid item xs={3}>
               <FormControl fullWidth>
                 <InputLabel htmlFor="tarefa_recurso">Recurso</InputLabel>
                 <Select
@@ -112,17 +148,17 @@ const CriarTarefa = ({handleClose, tarefas, setTarefas}) =>{
                   onChange={handleRecurso}
                   size="small"
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                  }} 
+                  }}
                 >
-                  <MenuItem value={'Recurso 1'}>Recurso 1</MenuItem>
-                  <MenuItem value={'Recurso 2'}>Recurso 2</MenuItem>
-                  <MenuItem value={'Recurso 3'}>Recurso 3</MenuItem>
+                  <MenuItem value={"Recurso 1"}>Recurso 1</MenuItem>
+                  <MenuItem value={"Recurso 2"}>Recurso 2</MenuItem>
+                  <MenuItem value={"Recurso 3"}>Recurso 3</MenuItem>
                 </Select>
               </FormControl>
             </Grid>
-            <Grid item xs={3}>  
+            <Grid item xs={3}>
               <FormControl fullWidth>
                 <InputLabel htmlFor="tarefa_recurso">Status</InputLabel>
                 <Select
@@ -132,39 +168,43 @@ const CriarTarefa = ({handleClose, tarefas, setTarefas}) =>{
                   onChange={handleStatus}
                   size="small"
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                  }} 
+                  }}
                 >
-                  <MenuItem value={'Aguardando'}>Aguardando</MenuItem>
-                  <MenuItem value={'Em Andamento'}>Em Andamento</MenuItem>
-                  <MenuItem value={'Concluída'}>Concluída</MenuItem>
+                  <MenuItem value={"Aguardando"}>Aguardando</MenuItem>
+                  <MenuItem value={"Em Andamento"}>Em Andamento</MenuItem>
+                  <MenuItem value={"Concluída"}>Concluída</MenuItem>
                 </Select>
               </FormControl>
             </Grid>
             <Grid container spacing={2} pl={2} mt={2}>
               <Grid item xs={1}>
-                <Button size="small" variant="contained" onClick={handleSalvar}>Salvar</Button>
-              </Grid>  
-              <Grid item xs={1}>  
-                <Button size="small" variant="outlined" onClick={handleClose}>Cancelar</Button>  
+                <Button size="small" variant="contained" onClick={handleSalvar}>
+                  Salvar
+                </Button>
               </Grid>
-            </Grid>  
+              <Grid item xs={1}>
+                <Button size="small" variant="outlined" onClick={handleClose}>
+                  Cancelar
+                </Button>
+              </Grid>
+            </Grid>
           </Grid>
         </CardContent>
       </Card>
     </Grid>
   );
-}
+};
 
 const style = {
-  position: 'absolute',
-  top: '50%',
-  left: '50%',
-  transform: 'translate(-50%, -50%)',
-  width: '60%',
-  bgcolor: 'background.paper',
+  position: "absolute",
+  top: "50%",
+  left: "50%",
+  transform: "translate(-50%, -50%)",
+  width: "60%",
+  bgcolor: "background.paper",
   p: 4,
 };
 
-export default CriarTarefa;
\ No newline at end of file
+export default CriarTarefa;
diff --git a/modulo10/template-materialui/src/pages/tarefa/EditarTarefa.jsx b/modulo10/template-materialui/src/pages/tarefa/EditarTarefa.jsx
index d9fcd44..bf7d1fe 100644
--- a/modulo10/template-materialui/src/pages/tarefa/EditarTarefa.jsx
+++ b/modulo10/template-materialui/src/pages/tarefa/EditarTarefa.jsx
@@ -1,24 +1,29 @@
-import React, {useState, useEffect} from 'react';
-import { FormControl, InputLabel, Input, FormHelperText } from '@mui/material';
-import MenuItem from '@mui/material/MenuItem';
-import Select from '@mui/material/Select';
-import Grid from '@mui/material/Grid';
-import Card from '@mui/material/Card';
-import CardHeader from '@mui/material/CardHeader';
-import CardContent from '@mui/material/CardContent';
-import CardActions from '@mui/material/CardActions';
-import Button from '@mui/material/Button';
+import React, { useState, useEffect } from "react";
+import { FormControl, InputLabel, Input, FormHelperText } from "@mui/material";
+import MenuItem from "@mui/material/MenuItem";
+import Select from "@mui/material/Select";
+import Grid from "@mui/material/Grid";
+import Card from "@mui/material/Card";
+import CardHeader from "@mui/material/CardHeader";
+import CardContent from "@mui/material/CardContent";
+import Button from "@mui/material/Button";
 
 //Declaração do componente EditarTarefa, recebendo como props, do Componente ListarTarefa, os states handCloseEditar,
 // idTarefaSelecionada, tarefas, tarefa e setTarefas
-const EditarTarefa = ({handleCloseEditar, idTarefaSelecionada, tarefas, tarefa, setTarefas}) =>{
-  const [idTarefa, setIdTarefa] = useState();
-  const [tituloTarefa, setTituloTarefa] = useState('');
-  const [descricaoTarefa, setDescricaoTarefa] = useState('');
-  const [inicioTarefa, setInicioTarefa] = useState('');
-  const [fimTarefa, setFimTarefa] = useState('');
-  const [recursoTarefa, setRecursoTarefa] = useState('');
-  const [statusTarefa, setStatusTarefa] = useState('');
+const EditarTarefa = ({
+  handleCloseEditar,
+  idTarefaSelecionada,
+  tarefas,
+  tarefa,
+  setTarefas,
+}) => {
+  const [, /* idTarefa */ setIdTarefa] = useState();
+  const [tituloTarefa, setTituloTarefa] = useState("");
+  const [descricaoTarefa, setDescricaoTarefa] = useState("");
+  const [inicioTarefa, setInicioTarefa] = useState("");
+  const [fimTarefa, setFimTarefa] = useState("");
+  const [recursoTarefa, setRecursoTarefa] = useState("");
+  const [statusTarefa, setStatusTarefa] = useState("");
 
   //Abaixo setamos os valores dos states (que popularão o formulário mais abaixo) com os valores do state Tarefa,
   //  recebido como props do componente ListarTarefa.
@@ -31,7 +36,8 @@ const EditarTarefa = ({handleCloseEditar, idTarefaSelecionada, tarefas, tarefa,
     setFimTarefa(tarefa.fimTarefa);
     setRecursoTarefa(tarefa.recursoTarefa);
     setStatusTarefa(tarefa.statusTarefa);
-  },[]);
+    // eslint-disable-next-line react-hooks/exhaustive-deps
+  }, []);
 
   const handleRecurso = (event) => {
     setRecursoTarefa(event.target.value);
@@ -44,18 +50,19 @@ const EditarTarefa = ({handleCloseEditar, idTarefaSelecionada, tarefas, tarefa,
   const handleEditar = () => {
     //console.log(`id: ${idTarefa} \n titulo: ${tituloTarefa} \n descrição: ${descricaoTarefa} \n inicio: ${inicioTarefa} \n fim: ${fimTarefa} \n recurso: ${recursoTarefa} \n status: ${statusTarefa}`);
     //console.log('idTarefaSelecionada: ' + idTarefaSelecionada);
-    setTarefas(current =>
-      current.map(obj => {
+    setTarefas((current) =>
+      current.map((obj) => {
         if (obj.idTarefa === idTarefaSelecionada) {
-          console.log('obj: ' + JSON.stringify(obj));          
-          return {...obj, 
-              idTarefa:idTarefaSelecionada,
-              tituloTarefa:tituloTarefa,
-              descricaoTarefa:descricaoTarefa,
-              inicioTarefa:inicioTarefa,
-              fimTarefa:fimTarefa,
-              recursoTarefa:recursoTarefa,
-              statusTarefa:statusTarefa
+          console.log("obj: " + JSON.stringify(obj));
+          return {
+            ...obj,
+            idTarefa: idTarefaSelecionada,
+            tituloTarefa: tituloTarefa,
+            descricaoTarefa: descricaoTarefa,
+            inicioTarefa: inicioTarefa,
+            fimTarefa: fimTarefa,
+            recursoTarefa: recursoTarefa,
+            statusTarefa: statusTarefa,
           };
         }
 
@@ -67,55 +74,90 @@ const EditarTarefa = ({handleCloseEditar, idTarefaSelecionada, tarefas, tarefa,
     handleCloseEditar();
   };
 
-  return(
+  return (
     <Grid container spacing={2}>
       <Card sx={style}>
-        <CardHeader
-          title="Tarefas"
-          subheader="Edição de Tarefas"
-        /> 
-        <CardContent sx={{
-          width: '95%',
-          maxWidth: '100%',
-        }}>
+        <CardHeader title="Tarefas" subheader="Edição de Tarefas" />
+        <CardContent
+          sx={{
+            width: "95%",
+            maxWidth: "100%",
+          }}
+        >
           <Grid item xs={12}>
             <FormControl fullWidth>
-              <Input id="tarefa_titulo" aria-describedby="tarefa_titulo_helper_text" value={tituloTarefa} onChange={e => { setTituloTarefa(e.target.value) }} />
-              <FormHelperText id="tarefa_titulo_helper_text">Título da Tarefa.</FormHelperText>
+              <Input
+                id="tarefa_titulo"
+                aria-describedby="tarefa_titulo_helper_text"
+                value={tituloTarefa}
+                onChange={(e) => {
+                  setTituloTarefa(e.target.value);
+                }}
+              />
+              <FormHelperText id="tarefa_titulo_helper_text">
+                Título da Tarefa.
+              </FormHelperText>
             </FormControl>
           </Grid>
-          <Grid item xs={12}>  
+          <Grid item xs={12}>
             <FormControl fullWidth>
-              <Input id="tarefa_descricao" aria-describedby="tarefa_descricao_helper_text" value={descricaoTarefa} onChange={e => { setDescricaoTarefa(e.target.value) }} />
-              <FormHelperText id="tarefa_descricao_helper_text">Descrição da Tarefa.</FormHelperText>
+              <Input
+                id="tarefa_descricao"
+                aria-describedby="tarefa_descricao_helper_text"
+                value={descricaoTarefa}
+                onChange={(e) => {
+                  setDescricaoTarefa(e.target.value);
+                }}
+              />
+              <FormHelperText id="tarefa_descricao_helper_text">
+                Descrição da Tarefa.
+              </FormHelperText>
             </FormControl>
           </Grid>
           <Grid container spacing={2} mt={1}>
-            <Grid item xs={3}>  
+            <Grid item xs={3}>
               <FormControl>
-                <Input id="tarefa_inicio" type="date" aria-describedby="tarefa_inicio_helper_text" value={inicioTarefa} onChange={e => { setInicioTarefa(e.target.value) }}
+                <Input
+                  id="tarefa_inicio"
+                  type="date"
+                  aria-describedby="tarefa_inicio_helper_text"
+                  value={inicioTarefa}
+                  onChange={(e) => {
+                    setInicioTarefa(e.target.value);
+                  }}
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                    paddingLeft:'13px'
-                  }} 
+                    paddingLeft: "13px",
+                  }}
                 />
-                <FormHelperText id="tarefa_inicio_helper_text">Início da Tarefa.</FormHelperText>
+                <FormHelperText id="tarefa_inicio_helper_text">
+                  Início da Tarefa.
+                </FormHelperText>
               </FormControl>
-            </Grid>  
-            <Grid item xs={3}>  
+            </Grid>
+            <Grid item xs={3}>
               <FormControl>
-                <Input id="tarefa_fim" type="date" aria-describedby="tarefa_fim_helper_text" value={fimTarefa} onChange={e => { setFimTarefa(e.target.value) }}
+                <Input
+                  id="tarefa_fim"
+                  type="date"
+                  aria-describedby="tarefa_fim_helper_text"
+                  value={fimTarefa}
+                  onChange={(e) => {
+                    setFimTarefa(e.target.value);
+                  }}
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                    paddingLeft:'13px'
-                  }} 
+                    paddingLeft: "13px",
+                  }}
                 />
-                <FormHelperText id="tarefa_fim_helper_text">Fim da Tarefa.</FormHelperText>
+                <FormHelperText id="tarefa_fim_helper_text">
+                  Fim da Tarefa.
+                </FormHelperText>
               </FormControl>
             </Grid>
-            <Grid item xs={3}>  
+            <Grid item xs={3}>
               <FormControl fullWidth>
                 <InputLabel htmlFor="tarefa_recurso">Recurso</InputLabel>
                 <Select
@@ -125,17 +167,17 @@ const EditarTarefa = ({handleCloseEditar, idTarefaSelecionada, tarefas, tarefa,
                   onChange={handleRecurso}
                   size="small"
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                  }} 
+                  }}
                 >
-                  <MenuItem value={'Recurso 1'}>Recurso 1</MenuItem>
-                  <MenuItem value={'Recurso 2'}>Recurso 2</MenuItem>
-                  <MenuItem value={'Recurso 3'}>Recurso 3</MenuItem>
+                  <MenuItem value={"Recurso 1"}>Recurso 1</MenuItem>
+                  <MenuItem value={"Recurso 2"}>Recurso 2</MenuItem>
+                  <MenuItem value={"Recurso 3"}>Recurso 3</MenuItem>
                 </Select>
               </FormControl>
             </Grid>
-            <Grid item xs={3}>  
+            <Grid item xs={3}>
               <FormControl fullWidth>
                 <InputLabel htmlFor="tarefa_recurso">Status</InputLabel>
                 <Select
@@ -145,39 +187,47 @@ const EditarTarefa = ({handleCloseEditar, idTarefaSelecionada, tarefas, tarefa,
                   onChange={handleStatus}
                   size="small"
                   sx={{
-                    color:'rgba(0, 0, 0, 0.6)',
+                    color: "rgba(0, 0, 0, 0.6)",
                     fontWeight: 400,
-                  }} 
+                  }}
                 >
-                  <MenuItem value={'Aguardando'}>Aguardando</MenuItem>
-                  <MenuItem value={'Em Andamento'}>Em Andamento</MenuItem>
-                  <MenuItem value={'Concluída'}>Concluída</MenuItem>
+                  <MenuItem value={"Aguardando"}>Aguardando</MenuItem>
+                  <MenuItem value={"Em Andamento"}>Em Andamento</MenuItem>
+                  <MenuItem value={"Concluída"}>Concluída</MenuItem>
                 </Select>
               </FormControl>
             </Grid>
             <Grid container spacing={2} pl={2} mt={2}>
               <Grid item xs={1}>
-                <Button size="small" variant="contained" onClick={handleEditar}>Salvar</Button>
-              </Grid>  
-              <Grid item xs={1}>  
-                <Button size="small" variant="outlined" onClick={handleCloseEditar}>Cancelar</Button>  
+                <Button size="small" variant="contained" onClick={handleEditar}>
+                  Salvar
+                </Button>
+              </Grid>
+              <Grid item xs={1}>
+                <Button
+                  size="small"
+                  variant="outlined"
+                  onClick={handleCloseEditar}
+                >
+                  Cancelar
+                </Button>
               </Grid>
-            </Grid>  
+            </Grid>
           </Grid>
         </CardContent>
       </Card>
     </Grid>
   );
-}
+};
 
 const style = {
-  position: 'absolute',
-  top: '50%',
-  left: '50%',
-  transform: 'translate(-50%, -50%)',
-  width: '60%',
-  bgcolor: 'background.paper',
+  position: "absolute",
+  top: "50%",
+  left: "50%",
+  transform: "translate(-50%, -50%)",
+  width: "60%",
+  bgcolor: "background.paper",
   p: 4,
 };
 
-export default EditarTarefa;
\ No newline at end of file
+export default EditarTarefa;
diff --git a/modulo10/template-materialui/src/pages/tarefa/ListarTarefa.jsx b/modulo10/template-materialui/src/pages/tarefa/ListarTarefa.jsx
index 8faf540..59f0fe2 100644
--- a/modulo10/template-materialui/src/pages/tarefa/ListarTarefa.jsx
+++ b/modulo10/template-materialui/src/pages/tarefa/ListarTarefa.jsx
@@ -1,44 +1,100 @@
-import React, { useState, useEffect } from 'react';
-import Table from '@mui/material/Table';
-import TableBody from '@mui/material/TableBody';
-import TableCell from '@mui/material/TableCell';
-import TableContainer from '@mui/material/TableContainer';
-import TableHead from '@mui/material/TableHead';
-import TableRow from '@mui/material/TableRow';
-import Paper from '@mui/material/Paper';
-import Card from '@mui/material/Card';
-import CardHeader from '@mui/material/CardHeader';
-import CardContent from '@mui/material/CardContent';
-import CardActions from '@mui/material/CardActions';
-import Button from '@mui/material/Button';
-import DeleteIcon from '@mui/icons-material/Delete';
-import EditIcon from '@mui/icons-material/Edit';
-import Modal from '@mui/material/Modal';
+import React, { useState, useEffect } from "react";
+import Table from "@mui/material/Table";
+import TableBody from "@mui/material/TableBody";
+import TableCell from "@mui/material/TableCell";
+import TableContainer from "@mui/material/TableContainer";
+import TableHead from "@mui/material/TableHead";
+import TableRow from "@mui/material/TableRow";
+import Paper from "@mui/material/Paper";
+import Card from "@mui/material/Card";
+import CardHeader from "@mui/material/CardHeader";
+import CardContent from "@mui/material/CardContent";
+import CardActions from "@mui/material/CardActions";
+import Button from "@mui/material/Button";
+import DeleteIcon from "@mui/icons-material/Delete";
+import EditIcon from "@mui/icons-material/Edit";
+import Modal from "@mui/material/Modal";
 
-import CriarTarefa from './CriarTarefa';
-import EditarTarefa from './EditarTarefa';
+import CriarTarefa from "./CriarTarefa";
+import EditarTarefa from "./EditarTarefa";
 
 //A função abaixo é usada para criar o array contendo os dados iniciais da listagem de tarefas.
 function createData(
-  idTarefa: number,
-  tituloTarefa: string,
-  descricaoTarefa: string,
-  inicioTarefa: string,
-  fimTarefa: string,
-  statusTarefa: string,
-  recursoTarefa: string,
+  idTarefa,
+  tituloTarefa,
+  descricaoTarefa,
+  inicioTarefa,
+  fimTarefa,
+  statusTarefa,
+  recursoTarefa,
 ) {
-  return { idTarefa, tituloTarefa, descricaoTarefa, inicioTarefa, fimTarefa, statusTarefa, recursoTarefa };
+  return {
+    idTarefa,
+    tituloTarefa,
+    descricaoTarefa,
+    inicioTarefa,
+    fimTarefa,
+    statusTarefa,
+    recursoTarefa,
+  };
 }
 
 //Definição do array contendo os dados iniciais da listagem de tarefas
 const initialRows = [
-  createData(1, 'Tarefa 1', 'Descrição da Tarefa 1', '2022-01-01', '2022-01-02', 'Concluída', 'Recurso 1'),
-  createData(2, 'Tarefa 2', 'Descrição da Tarefa 2', '2022-01-03', '2022-01-04', 'Em Andamento', 'Recurso 2'),
-  createData(3, 'Tarefa 3', 'Descrição da Tarefa 3', '2022-01-04', '2022-01-05', 'Em Andamento', 'Recurso 3'),
-  createData(4, 'Tarefa 4', 'Descrição da Tarefa 4', '2022-01-05', '2022-01-06', 'Em Andamento', 'Recurso 4'),
-  createData(5, 'Tarefa 5', 'Descrição da Tarefa 5', '2022-01-06', '2022-01-07', 'Em Andamento', 'Recurso 5'),
-  createData(6, 'Tarefa 6', 'Descrição da Tarefa 6', '2022-01-07', '2022-01-08', 'Aguardando', 'Recurso 6'),
+  createData(
+    1,
+    "Tarefa 1",
+    "Descrição da Tarefa 1",
+    "2022-01-01",
+    "2022-01-02",
+    "Concluída",
+    "Recurso 1",
+  ),
+  createData(
+    2,
+    "Tarefa 2",
+    "Descrição da Tarefa 2",
+    "2022-01-03",
+    "2022-01-04",
+    "Em Andamento",
+    "Recurso 2",
+  ),
+  createData(
+    3,
+    "Tarefa 3",
+    "Descrição da Tarefa 3",
+    "2022-01-04",
+    "2022-01-05",
+    "Em Andamento",
+    "Recurso 3",
+  ),
+  createData(
+    4,
+    "Tarefa 4",
+    "Descrição da Tarefa 4",
+    "2022-01-05",
+    "2022-01-06",
+    "Em Andamento",
+    "Recurso 4",
+  ),
+  createData(
+    5,
+    "Tarefa 5",
+    "Descrição da Tarefa 5",
+    "2022-01-06",
+    "2022-01-07",
+    "Em Andamento",
+    "Recurso 5",
+  ),
+  createData(
+    6,
+    "Tarefa 6",
+    "Descrição da Tarefa 6",
+    "2022-01-07",
+    "2022-01-08",
+    "Aguardando",
+    "Recurso 6",
+  ),
 ];
 
 //Componente ListarTarefa
@@ -56,13 +112,13 @@ const ListarTarefa = () => {
   //O array definido acima é setado como conteúdo do state Tarefas na renderização inicial do componente.
   useEffect(() => {
     setTarefas(initialRows);
-  },[]);
+  }, []);
 
   const handleEditar = (id) => {
     setIdTarefaSelecionada(id);
 
     //Objeto local para armazenamento da tarefa filtrada de acordo com a seleção do usuário
-    let tarefaParaEditar = tarefas.filter(obj => {
+    let tarefaParaEditar = tarefas.filter((obj) => {
       return obj.idTarefa === id;
     })[0];
 
@@ -70,100 +126,127 @@ const ListarTarefa = () => {
     setTarefa(tarefaParaEditar);
 
     //Seta como true o state responsável pela exibição do Model de Editar Tarefa
-    setOpenEditar(true)
+    setOpenEditar(true);
   };
 
   const handleDeletar = (id) => {
-    setTarefas(current =>
-      current.filter(tarefa => {
+    setTarefas((current) =>
+      current.filter((tarefa) => {
         return tarefa.idTarefa !== id;
       }),
     );
   };
 
-    return(
+  return (
     <>
-    <Card>
-        <CardHeader
-          title="Tarefas"
-          subheader="Listagem de Tarefas"
-        /> 
+      <Card>
+        <CardHeader title="Tarefas" subheader="Listagem de Tarefas" />
         <CardContent>
-            <TableContainer component={Paper}>
-            <Table sx={{ minWidth: 650 }} size="small" aria-label="a dense table">
-                <TableHead>
+          <TableContainer component={Paper}>
+            <Table
+              sx={{ minWidth: 650 }}
+              size="small"
+              aria-label="a dense table"
+            >
+              <TableHead>
                 <TableRow>
-                    <TableCell>#</TableCell>
-                    <TableCell>Título</TableCell>
-                    <TableCell align="right">Descrição</TableCell>
-                    <TableCell align="right">Data de Início</TableCell>
-                    <TableCell align="right">Data de Finalização</TableCell>
-                    <TableCell align="right">Status</TableCell>
-                    <TableCell align="right">Recurso</TableCell>
-                    <TableCell align="left"></TableCell>
-                    <TableCell align="left"></TableCell>
+                  <TableCell>#</TableCell>
+                  <TableCell>Título</TableCell>
+                  <TableCell align="right">Descrição</TableCell>
+                  <TableCell align="right">Data de Início</TableCell>
+                  <TableCell align="right">Data de Finalização</TableCell>
+                  <TableCell align="right">Status</TableCell>
+                  <TableCell align="right">Recurso</TableCell>
+                  <TableCell align="left"></TableCell>
+                  <TableCell align="left"></TableCell>
                 </TableRow>
-                </TableHead>
-                <TableBody>
+              </TableHead>
+              <TableBody>
                 {tarefas.map((row, indice) => (
-                    <TableRow
+                  <TableRow
                     key={indice}
-                    sx={{ '&:last-child td, &:last-child th': { border: 0 } }}
-                    >
-                      <TableCell component="th" scope="row">
-                          {row.idTarefa}
-                      </TableCell>
-                      <TableCell component="th" scope="row">
-                          {row.tituloTarefa}
-                      </TableCell>
-                      <TableCell align="right">{row.descricaoTarefa}</TableCell>
-                      <TableCell align="right">{row.inicioTarefa}</TableCell>
-                      <TableCell align="right">{row.fimTarefa}</TableCell>
-                      <TableCell align="right">{row.statusTarefa}</TableCell>
-                      <TableCell align="right">{row.recursoTarefa}</TableCell>
-                      <TableCell align="center">
-                        <Button variant="contained" color="success" onClick={() => handleEditar(row.idTarefa)}><EditIcon fontSize="small" /></Button>            
-                      </TableCell>
-                      <TableCell align="center">
-                        <Button variant="contained" color="error" onClick={() => handleDeletar(row.idTarefa)}><DeleteIcon fontSize="small" /></Button>            
-                      </TableCell>
-                    </TableRow>
+                    sx={{ "&:last-child td, &:last-child th": { border: 0 } }}
+                  >
+                    <TableCell component="th" scope="row">
+                      {row.idTarefa}
+                    </TableCell>
+                    <TableCell component="th" scope="row">
+                      {row.tituloTarefa}
+                    </TableCell>
+                    <TableCell align="right">{row.descricaoTarefa}</TableCell>
+                    <TableCell align="right">{row.inicioTarefa}</TableCell>
+                    <TableCell align="right">{row.fimTarefa}</TableCell>
+                    <TableCell align="right">{row.statusTarefa}</TableCell>
+                    <TableCell align="right">{row.recursoTarefa}</TableCell>
+                    <TableCell align="center">
+                      <Button
+                        variant="contained"
+                        color="success"
+                        onClick={() => handleEditar(row.idTarefa)}
+                      >
+                        <EditIcon fontSize="small" />
+                      </Button>
+                    </TableCell>
+                    <TableCell align="center">
+                      <Button
+                        variant="contained"
+                        color="error"
+                        onClick={() => handleDeletar(row.idTarefa)}
+                      >
+                        <DeleteIcon fontSize="small" />
+                      </Button>
+                    </TableCell>
+                  </TableRow>
                 ))}
-                </TableBody>
+              </TableBody>
             </Table>
-            </TableContainer>
+          </TableContainer>
         </CardContent>
         <CardActions>
-            <Button size="small" variant="contained" onClick={handleOpen}>Criar Tarefa</Button>
-            <Button size="small" variant="outlined">Cancelar</Button>
-      </CardActions> 
-    </Card>
-    <div>
-      <Modal
-        open={open}
-        onClose={handleClose}
-        aria-labelledby="modal-modal-title"
-        aria-describedby="modal-modal-description"
-      >
-        <div>
-          <CriarTarefa handleClose={handleClose} tarefas={tarefas} setTarefas={setTarefas} />
-        </div>
-      </Modal>  
-    </div>
-    <div>
-      <Modal
-        open={openEditar}
-        onClose={handleCloseEditar}
-        aria-labelledby="modal-modal-title"
-        aria-describedby="modal-modal-description"
-      >
-        <div>
-          <EditarTarefa handleCloseEditar={handleCloseEditar} idTarefaSelecionada={idTarefaSelecionada} tarefas={tarefas} tarefa={tarefa} setTarefas={setTarefas} />
-        </div>
-      </Modal>  
-    </div>
-  </>    
- );
+          <Button size="small" variant="contained" onClick={handleOpen}>
+            Criar Tarefa
+          </Button>
+          <Button size="small" variant="outlined">
+            Cancelar
+          </Button>
+        </CardActions>
+      </Card>
+      <div>
+        <Modal
+          open={open}
+          onClose={handleClose}
+          aria-labelledby="modal-modal-title"
+          aria-describedby="modal-modal-description"
+        >
+          <div>
+            <CriarTarefa
+              handleClose={handleClose}
+              tarefas={tarefas}
+              setTarefas={setTarefas}
+            />
+          </div>
+        </Modal>
+      </div>
+      <div>
+        <Modal
+          open={openEditar}
+          onClose={handleCloseEditar}
+          aria-labelledby="modal-modal-title"
+          aria-describedby="modal-modal-description"
+        >
+          <div>
+            <EditarTarefa
+              handleCloseEditar={handleCloseEditar}
+              idTarefaSelecionada={idTarefaSelecionada}
+              tarefas={tarefas}
+              tarefa={tarefa}
+              setTarefas={setTarefas}
+            />
+          </div>
+        </Modal>
+      </div>
+    </>
+  );
 };
- 
-export default ListarTarefa;
\ No newline at end of file
+
+export default ListarTarefa;
diff --git a/modulo10/template-materialui/src/reportWebVitals.js b/modulo10/template-materialui/src/reportWebVitals.js
index 5253d3a..9ecd33f 100644
--- a/modulo10/template-materialui/src/reportWebVitals.js
+++ b/modulo10/template-materialui/src/reportWebVitals.js
@@ -1,6 +1,6 @@
-const reportWebVitals = onPerfEntry => {
+const reportWebVitals = (onPerfEntry) => {
   if (onPerfEntry && onPerfEntry instanceof Function) {
-    import('web-vitals').then(({ getCLS, getFID, getFCP, getLCP, getTTFB }) => {
+    import("web-vitals").then(({ getCLS, getFID, getFCP, getLCP, getTTFB }) => {
       getCLS(onPerfEntry);
       getFID(onPerfEntry);
       getFCP(onPerfEntry);
diff --git a/modulo10/template-materialui/src/setupTests.js b/modulo10/template-materialui/src/setupTests.js
index 8f2609b..1dd407a 100644
--- a/modulo10/template-materialui/src/setupTests.js
+++ b/modulo10/template-materialui/src/setupTests.js
@@ -2,4 +2,4 @@
 // allows you to do things like:
 // expect(element).toHaveTextContent(/react/i)
 // learn more: https://github.com/testing-library/jest-dom
-import '@testing-library/jest-dom';
+import "@testing-library/jest-dom";
  ```
</details>

## Aplicação React de Gerenciamento de Projetos e Tarefas

Projeto criado com as bibliotecas React JS e Material UI.

### Passo-a-passo para execução

1. Clonar o repositório
2. Localmente, entrar na pasta do projeto e instalar as dependências:
   `npm install`
3. Executar a aplicação:
   `npm start`
