<h1>Formulieren</h1>

<p></p>

<div class="col-lg-5 p-5">
    <h3 class="mb-3">Neem contact op</h3>
	<div class="no-shadow form-container svelte-nixaq6">
		<form method="POST" novalidate="">
			<div class="form-floating mb-3">
				<input
					required=""
					type="text"
					class="form-control form-control-lg fs-5"
					id="naam"
					placeholder="typ uw naam…"
					name="naam"
				/> <label for="naam" class="form-label">Naam</label>
			</div>
			<div class="form-floating mb-3">
				<input
					required=""
					type="email"
					class="form-control form-control-lg fs-5"
					id="email"
					placeholder="typ uw e-mailadres…"
					name="email"
				/> <label for="email" class="form-label">E-mailadres</label>
			</div>
			<div class="form-floating mb-3">
				<input
					required=""
					type="text"
					class="form-control form-control-lg fs-5"
					id="onderwerp"
					placeholder="typ een onderwerp…"
					name="onderwerp"
				/> <label for="onderwerp" class="form-label">Onderwerp</label>
			</div>
			<div class="form-floating mb-3">
				<textarea
					required=""
					class="form-control form-control-lg fs-5"
					id="bericht"
					rows="3"
					placeholder="typ uw bericht…"
					name="bericht"
					style="height: 100px;"
				></textarea> <label for="bericht" class="form-label">Bericht</label>
			</div>

            <div class="no-shadow d-flex justify-content-end mt-3">
                <button type="submit" class="btn btn-primary">Verstuur</button>
            </div>
		</form>
	</div>
</div>

<style>
	div {
		box-shadow: var(--box-shadow);
		border-radius: var(--border-radius);
	}

	div.no-shadow {
		box-shadow: none;
		border-radius: var(--border-radius);
	}
</style>
