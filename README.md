# soloEnterosAngular

## ¿Como usarlo?

### Importar la directiva en app.module.ts
import {OnlynumberDirective} from '../../src/app/onlynumber.directive';

### Colocarla en los NgModules de app.module.ts
@NgModule({
  declarations: [
	OnlynumberDirective,

### Usarla en el template de la siguiente manera
<input [disabled]="habilitarEstado" type="text" class="form-control" placeholder="Ingrese el RUC" [(ngModel)]="cliente.ruc" appOnlynumber>
